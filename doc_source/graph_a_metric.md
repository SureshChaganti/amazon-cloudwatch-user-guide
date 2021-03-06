# Graph a Metric<a name="graph_a_metric"></a>

You can select metrics and create graphs of the data using the CloudWatch console\.

CloudWatch supports the following statistics on metrics: `Average`, `Minimum`, `Maximum`, `Sum`, and `SampleCount`\. For more information, see [Statistics](cloudwatch_concepts.md#Statistic)\.

You can view your data at different granularities\. For example, you can choose a detailed view \(for example 1 minute\), which can be useful when troubleshooting\. You can choose a less detailed view \(for example, 1 hour\), which can be useful when viewing a broader time range \(for example, 3 days\) so that you can see trends over time\. For more information, see [Periods](cloudwatch_concepts.md#CloudWatchPeriods)\.

## Create a Graph<a name="create-metric-graph"></a>

**To graph a metric**

1. Open the CloudWatch console at [https://console\.aws\.amazon\.com/cloudwatch/](https://console.aws.amazon.com/cloudwatch/)\.

1. In the navigation pane, choose **Metrics**\.

1. On the **All metrics** tab, type a search term in the search field, such as a metric name or resource name, and press Enter\.

   For example, if you search for the **CPUUtilization** metric, you see the namespaces and dimensions with this metric\.

1. Select one of the results for your search to view the metrics\.

1. To graph one or more metrics, select the check box next to each metric\. To select all metrics, select the check box in the heading row of the table\.

1. To view more information about the metric being graphed, hover over the legend\.

1. Horizontal annotations can help graph users quickly see when a metric has spiked to a certain level, or whether the metric is within a predefined range\. To add a horizontal annotation, choose **Graph options**, **Add horizontal annotation**:

   1. For **Label**, type a label for the annotation\.

   1. For **Value**, type the metric value where the horizontal annotation appears\.

   1. For **Fill**, specify whether to use fill shading with this annotation\. For example, choose `Above` or `Below` for the corresponding area to be filled\. If you specify `Between`, another `Value` field appears, and the area of the graph between the two values is filled\.

   1. For **Axis**, specify whether the numbers in `Value` refer to the metric associated with the left Y\-axis or the right Y\-axis, if the graph includes multiple metrics\.

      You can change the fill color of an annotation by choosing the color square in the left column of the annotation\. 

   Repeat these steps to add multiple horizontal annotations to the same graph\.

   To hide an annotation, clear the checkbox in the left column for that annotation\.

   To delete an annotation, choose **x** in the **Actions** column\.

1. To get a URL for your graph, choose **Actions**, **Share**\. Copy the URL and save it or share it\.

1. To add your graph to a dashboard, choose **Actions**, **Add to dashboard**\.

## Update a Graph<a name="update-metric-graph"></a>

**To update your graph**

1. To change the name of the graph, choose the pencil icon\.

1. To change the time range, select one of the predefined values or choose **custom**\. For more information, see [Modify the Time Range or Time Zone Format for a Graph](modify_graph_date_time.md)\.

1. To change the statistic, choose the **Graphed metrics** tab\. Choose the column heading or an individual value, and then choose one of the statistics or predefined percentiles, or specify a custom percentile \(for example, p95\.45\)\.

1. To change the period, choose the **Graphed metrics** tab\. Choose the column heading or an individual value, and then choose a different value\.

1. To add a horizontal annotation, choose **Graph options**, **Add horizontal annotation**:

   1. For **Label**, type a label for the annotation\.

   1. For **Value**, type the metric value where the horizontal annotation appears\.

   1. For **Fill**, specify whether to use fill shading with this annotation\. For example, choose `Above` or `Below` for the corresponding area to be filled\. If you specify `Between`, another `Value` field appears, and the area of the graph between the two values is filled\.

   1. For **Axis**, specify whether the numbers in `Value` refer to the metric associated with the left Y\-axis or the right Y\-axis, if the graph includes multiple metrics\.

      You can change the fill color of an annotation by choosing the color square in the left column of the annotation\. 

   Repeat these steps to add multiple horizontal annotations to the same graph\.

   To hide an annotation, clear the checkbox in the left column for that annotation\.

   To delete an annotation, choose **x** in the **Actions** column\.

1. To change the refresh interval, choose **Refresh options**, and then select **Auto refresh** or choose **1 Minute**, **2 Minutes**, **5 Minutes**, or **15 Minutes**\.

## Duplicate a Metric<a name="duplicate-metric-graph"></a>

**To duplicate a metric**

1. Choose the **Graphed metrics** tab\.

1. For **Actions**, choose the **Duplicate** icon\.  
![\[Duplicate a metric\]](http://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/images/metric_graph_duplicate.png)

1. Update the duplicate metric as needed\.