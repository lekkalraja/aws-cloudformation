
#### How CloudFormation Works!

* Templates have to be uploaded in s3 and then reference in the cloudformation console.
* We can't edit the existing stack, we can only update the existing stack by re-uploading modified .yaml or new .yaml file
* Stacks are identified by a name and should be unique in account region
* To delete all the underlying resources which was created by stack, needs to delete the stack.