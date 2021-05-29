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

#### CloudFormation Template Options
* Tags
* Permissions
* Notification Options
* `Rollback Configuration` : Specify alarms for CloudFormation to monitor when creating and updating the stack. If the operation breaches an alarm threshold, CloudFormation rolls it back
* `Stack Policy` : Defines the resources that you want to protect from unintentional updates during a stack update.
* `Stack Creation Options`
  * `Rollback On Failure`: Specifies whether the stack should be rolled back if stack creation fails.
  * `Timeout`: The number of minutes before a stack creation times out.
  * `Termination protection`: Prevents the stack from being accidentally deleted. Once created, you can update this through stack actions.


#### CloudFormation Building Blocks

##### Templates Components
* `Resources` : AWS Resources declared in the template
* `Parameters` : Dynamic inputs for template
* `Mappings` : Static variables for template
* `Outputs` : References to what has been created
* `Conditionals` : List of conditions to perform resource creation
* `Metadata`

##### Templates Helpers
* References
* Functions