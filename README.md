# AWS CloudFormation

### Pre-Requisites
- Basic Knowledge of Amazon Web Services is Required
- Knowledge on YAML is Required

* `AWS has over 200 products` so that it became very hard to manage all these manually or using some cli/scripts. so aws has created `CloudFormation` to manage all these in very easier way.
* `AWS CloudFormation` is a declarative way of outlining AWS Infrastructure for most of the aws services (almost every service). For [Documentation]([https://link](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html))

### Benefits
* Infrastructure as a code
* Estimate, Track, manage and save aws cost
* Productivity
* Separation of concern: Cross stacks, Nested stacks

##### Note : Leverage existing templates on the web and also the documentation.

* CloudFormation is AWS Native, state based.
* Ansible and Terraform are instruction based and it's very difficult to fully orchestrate the stacks and also these have to be update every time a new service or api option comes from AWS which will take a long time.