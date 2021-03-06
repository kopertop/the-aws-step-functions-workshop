---
title: 'Review workflow'
weight: 43
---

Navigate to [Step Functions in the console](https://console.aws.amazon.com/states/home) and click the state machine that starts with **"RequestResponseStateMachine"**. In this sample app we will wait for a specified delay, then we will publish to a SNS topic using the Request Response pattern.

When you specify a service in the `"Resource"` string of your task state, and you only provide the resource, Step Functions will wait for an HTTP response from the service API and then will immediately progress to the next state. Step Functions will not wait for a job to complete. This called the Request Response pattern.

Review the definition in Workflow Studio:

![Module 2 Workflow](/static/img/module-2/workflow.png)

Notice the `"Resource"` string of the task state below. This code designates a Request Response service integration pattern.

![Module 2 Code](/static/img/module-2/code.png)
