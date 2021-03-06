# Retrieving license usage data from the cluster

- [Available APIs](#available-apis)
- [Tracking license usage in multicluster environment](#tracking-license-usage-in-multicluster-environment)

## Available APIs

License Service collects and measures information about license usage of your IBM containerized software per cluster.

You can use a set of dedicated APIs to retrieve the following information:

- Retrieving an audit snapshot for the cluster
- Retrieving license usage of products on a cluster level
- Retrieving license usage of bundled products on the cluster level
- Retrieving information about License Service version
- Retrieving information about License Service health

To learn how to use the APIs to retrieve data and generate an audit snapshot, see [APIs for retrieving License Service data in IBM Knowledge Center](https://www.ibm.com/support/knowledgecenter/SSHKN6/license-service/1.x.x/retrieving.html).

## Tracking license usage in multicluster environment

You can use the data that is collected by License Service from individual clusters to track the cumulative license usage in a multicluster environment. The cumulative report is not required for audit, but it might give you a full overview of your license usage in the multicluster environment.
For more information, see the overview in [Tracking license usage in multicluster environment](https://www.ibm.com/support/knowledgecenter/SSHKN6/license-service/1.x.x/multicluster.html).

You can use the non-automated procedure to create a cumulative report for your environment. For more information, see [Manually tracking license usage in multicluster environment in IBM Knowledge Center](https://www.ibm.com/support/knowledgecenter/SSHKN6/license-service/1.x.x/multicluster_main.html).

### License Service Reporter

**Note:** License Service has recently been upgraded with an extension for tracking license usage in multicluster environment called License Service Reporter. However, at this point License Service Reporter is only supported with License Service instance that is shipped with IBM Cloud Platform Common Services and integrated with IBM Cloud Pak solutions.

If you have an IBM Cloud Pak deployed in your environment and you deployed License Service Reporter, you can configure a non-OpenShift cluster to deliver licensing data to License Service Reporter. For more information, see [Tracking license usage in multicluster environment with License Service Reporter](https://www.ibm.com/support/knowledgecenter/SSHKN6/license-service/1.x.x/license_reporter.html).

<b>Related links</b>
- [Go back to home page](../License_Service_main.md#documentation)
