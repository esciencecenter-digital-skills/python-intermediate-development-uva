---
title: "Section 6: Continuous Delivery"
colour: "#fafac8"
start: true
teaching: 5
exercises: 0
questions:
- "What are the benefits of Continuous Delivery and "

objectives:
- "Understand the benefits of Continuous Delivery."
keypoints:
- "Continuous Delivery automates the software release process, which enables you to deliver updates faster"
---

In this section of the course we will learn about Continuous Delivery and Continuous Deployment.

## What is Continuous Delivery?
We have learned how we can automate building, linting and testing our application automatically using BitBucket Pipelines.
Remember that certain commits would trigger a pipeline defined in a `bitbucket-pipelines.yml` file that runs on BitBucket's cloud server.

The next step is to also automate the deployment of the application through a BitBucket Pipeline. 
This is called Continuous Deployment or Continuous Delivery.

## What is the difference between Continuous Delivery and Continuous Deployment?
With Continuous Delivery we mean that the build, test, and staging environment deployment are all automated.
Also the production deployment process is automated, but it still requires a human to press a button before a new release is deployed to production.

With Continuous Deployment, there is no human gatekeeper anymore, the whole process is automated. 
For example, when a new merge is made into the main branch, and all builds and tests are successfully completed, 
the application is automatically deployed to production. This allows for an even swifter deployment cycle.

Depending on your needs you can choose one over the other.


> ## Exercise: What are benefits of Continuous Delivery and Continuous Deployment?
>
> What do you think are benefits of Continous Delivery/Continuous Deployment?
> Discuss with your neighbour.
>
> Time: 5 mins
> 
> > ## Solution
> > * Automated software release process
> > * Improve developer productivity
> > * Address bugs quickly
> > * Deliver updates fast
> > * Deployments are coupled to your version control system
> {: .solution}
{: .challenge}

In this section we will:
- Learn how we can use BitBucket Pipelines to automate the software release process.

{% include links.md %}

