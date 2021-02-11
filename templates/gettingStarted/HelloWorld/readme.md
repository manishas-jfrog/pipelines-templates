This template demonstrates how simple workflows can be defined and executed with JFrog Pipelines.

This pipeline example demonstrates the following:

* Creating a Git integration.
* Adding a Pipeline Source.
* Creating a GitRepo trigger, which will trigger a step when the contents of the source control repository change.
* Using inputResources and inputSteps to set up dependencies between steps and resources.
* Using environment variables (e.g. $res_myFirstRepo_commitSha) to extract information from inputResources.
* Using run state to pass information to downstream steps of a run.
* Using pipeline state to pass information to subsequent runs.
* Connecting dependent pipelines through resources

To customize and execute this template:
* Copy the values.yml.example file and customize it with your Git integration name and repository name
* Commit it to your source control repository
* Add the repository as a Pipeline Source
* Execute the pipeline

It's as simple as thatI !
