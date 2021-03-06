<!-- add-breadcrumbs -->
#Dashboard

> Introduced in Version 12

Dashboard provides an at-a-glance view of key performance indicators relevant to the business process.

Each Dashboard consists of one or more than one Dashboard Charts each of which are configured with a data source known as Dashboard Chart Source.

<img class="screenshot" alt="Accounting Dashboard" src="{{docs_base_url}}/assets/img/customize/dashboard-0.png">

### Create a new Dashboard

To create a new Dashboard, go to

`Dashboard > New`

### Add Chart to Dashboard

Add charts to this dashboard by either selecting existing `Dashboard Chart` or creating new ones.

<img class="screenshot" alt="Add Chart To Dashboard" src="{{docs_base_url}}/assets/img/customize/dashboard-1.png">

Save changes and Click on `Show Dashboard` button to see the dashboard.

<img class="screenshot" alt="Show Dashboard Button" src="{{docs_base_url}}/assets/img/customize/dashboard-6.png">

### Create New Dashboard Chart

To create a new Dashboard Chart, go to

`Dashboard Chart > New`

Provide a name for the chart, this will show up in the dashboard as the chart label and select a `Dashboard Chart Source` as the data source for this chart.

**Note:** New `Dashboard Chart Source` can only be created by the Administrator User in Developer Mode.

<img class="screenshot" alt="Select Dashboard Chart Source" src="{{docs_base_url}}/assets/img/customize/dashboard-2.png">

After setting the Chart Source field, the filters table will be shown.

Click the table to edit filters.

<img class="screenshot" alt="Filters Table" src="{{docs_base_url}}/assets/img/customize/dashboard-3.png">

A modal will be shown to set filters. Click `Set` to set filters.
<img class="screenshot" alt="Filters Modal" src="{{docs_base_url}}/assets/img/customize/dashboard-4.png">

After setting Chart Source field, Filters table will be updated with selected filter values.
<img class="screenshot" alt="Filters Table With Selected Filter Values" src="{{docs_base_url}}/assets/img/customize/dashboard-5.png">

### Use Dashboard

Every chart will be shown according to the fields set in the corresponding Dashboard Chart. The result from the dashboard chart source is cached to avoid redundant queries. Since the chart data can be stale, each chart will also show the last synced time.

<img class="screenshot" alt="Chart Options" src="{{docs_base_url}}/assets/img/customize/dashboard-7.png">

The filters used to generate the chart data can also be changed by clicking `Set Filters`. The chart will be refreshed automatically according to the recently set filters

<img class="screenshot" alt="Modal For Chart Filters" src="{{docs_base_url}}/assets/img/customize/dashboard-8.png">

To get the most recent data each chart has to be refreshed forcefully by clicking `Force Refresh` button from the dropdown menu
