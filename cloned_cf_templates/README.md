This is a directory where we copy the templates that GorillaStack keep in their S3 bucket. This is to make sure we always have a local copy. In order to refresh, run the following:

```
$ wget -N https://s3.amazonaws.com/cloudformation-stackset-sample-templates-us-east-1/AWSCloudFormationStackSetAdministrationRole.yml
$ wget -N https://s3.amazonaws.com/cloudformation-stackset-sample-templates-us-east-1/AWSCloudFormationStackSetExecutionRole.yml
$ wget -N https://gorillastack-autotag-releases.s3-ap-southeast-2.amazonaws.com/templates/autotag_event_main-template.json
$ wget -N https://gorillastack-autotag-releases.s3-ap-southeast-2.amazonaws.com/templates/autotag_event_collector-template.json
```