# Overview Of Power BI

## What is Power BI

Power BI is Self-service Business intelligence tool provided by Microsoft that lets you visualize your data and share insights to business users.
Make informed decisions quickly. Connect, model, and then explore your data with visual reports that you can collaborate, publish, and share. 

### The Parts of Power BI

* A Windows desktop application called Power BI Desktop.
* An online SaaS (Software as a Service) service called the Power BI service.
* Power BI mobile apps for Windows, iOS, and Android devices.

![Overview](./img/Overview.png)

## Power BI Architecture

Power BI is a combination of multiple application and add-ons which we can build reports and dashboards and share our solutions to business users. Parts of Power BI Products.

* Power BI Desktop.
* Power BI Service.
* Power BI Reporting Service.
* Power BI Mobile App.

![Architecture](./img/powerbiarchitecture.png)

### Power BI Desktop

Power BI Desktop is a free application you can install on your local computer that lets you connect to data sources, transform, and visualize your data. With Power BI Desktop, you can connect to multiple (Different) sources of data and combine them (often called modeling) into a data model. 
Data model lets you build visuals, and collections of visuals you can share as reports, with other people inside your organization. Most users who work on business intelligence projects use Power BI Desktop to create reports, and then use the Power BI service to share their reports with others.
The most common uses for Power BI Desktop are as follows:
* Connect to data 
* Transform and clean that data, to create a data model
* Create visuals, such as charts or graphs, that provide visual representations of the data
* Create reports that are collections of visuals, on one or more report pages

To Download Power BI Desktop, Click [Here](https://www.microsoft.com/en-us/download/details.aspx?id=58494)

We Can connect 100+ Data sources (SQL Server, Oracle, Flat files, web Based, SAP Data sources and Cloud (Azure and Share point List) Data sources using Power BI Data connectors. Once we connect to respective data source we can transform the data using Power BI Query Editor tool like cleaning the data, Parameters creations, merging and Appending the queries then build the data model and create Relationships between the tables in Power BI Data model pane then create the reports using required visualizations and Publish the report to Power BI Service.

![Desktop](./img/PowerBIDesktop.png)

### Power BI Desktop Options 

![Desktopoptions](./img/PowerBIDesktopoptions.png)

### Relationships

![Relationships](./img/PowerBIRelationships.png)

To know more details about Power BI Desktop click [here](https://docs.microsoft.com/en-us/power-bi/fundamentals/desktop-getting-started)
To know more details about connect data option click [here](https://docs.microsoft.com/en-us/power-bi/report-server/quickstart-create-powerbi-report)
To Know more details about data model click [here](https://docs.microsoft.com/en-us/learn/modules/model-data-power-bi/1-overview-power-bi)
To know more details about relationships click [here](https://docs.microsoft.com/en-us/power-bi/transform-model/desktop-create-and-manage-relationships#:~:text=You%20can%20manage%20how%20Power,The%20options%20for%20Relationships%20appear)
To Know more about DAX and Column\Measure creation click [here](https://docs.microsoft.com/en-us/power-bi/transform-model/desktop-tutorial-create-calculated-columns)

 
### Power BI Service

The Power BI service is a cloud-based service. It supports light report editing and collaboration for teams and organizations. You can share your report to business users.
You can create streaming data set in Power BI Service and build reports and dashboards using stream data set. Create new Dashboards in power BI Service combination of multiple reports visualizations.
You can create new app with collection of multiple repots visualization based on function area and import prebuild app from within organization or from Microsoft apps store.

To Login Power BI Service click [here](https://app.powerbi.com/)
To Know more details about Power BI Service click [here](https://docs.microsoft.com/en-us/power-bi/fundamentals/power-bi-service-overview)

![Service](./img/PowerBIService.png)

### PowerBIServiceOptions

![ServiceOptions](./img/PowerBIServiceOptions.png)

#### PowerBILicense

Here License part will play key role to create new workspace, publish reports to Power BI Service and distribute reports to within organization or users. Having three types of licenses.

* Power BI Free
* Power BI Pro
* Power BI Premium

#### Power BI Free

Power BI Free License comes with Office 365 E3 license you can  build reports in Power BI Desktop and publish reports to Power BI Service but you can share your reports and dashboards  to others or users its behave like my favorite folder.

#### Power BI Pro License

Using Pro license you can create new workspace and provide workspace access to others pro license works for each user.
You can publish reports in all workspaces based on access level given by workspace admin, share your reports to business users. Whoever accessing reports required pro license or workspace need to be in premium capacity.
Pro user can refresh data sets and it should be some limitations

#### Power BI Premium

Premium capacity license work in organization level if organization or workspace is there in premium capacity users can consume reports using their free license and pro License is not required. Will get more data source refresh capability using this license type.

To know more details about license type click [here](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-licensing-organization).
To know more details about pro and premium license click [here](https://powerbi.microsoft.com/en-us/pricing/)

### Power BI Report Server

The Power BI Report Server is similar to the Power BI Service. The only difference between these two is that Power BI Report Server is an on-premise platform. It is used by organizations who do not want to publish their reports on the cloud and are concerned about the security of their data.
Power BI Gateway component is used to connect and access on-premise data in secured networks. Power BI Gateways are generally used in organizations where data is kept in security and watch. Gateways help to extract the data and refresh data using direct queries 
Will categorized data sources in two types Cloud Data sources and On-premise data sources.

#### Cloud Data sources 

(like Share Point Folder , Share Point List, One drive, Azure cloud data etc ) if you build power BI report using these data sources then no need gateway connection to refresh the dataset in Power BI service, we can schedule the datasets in power BI service level. Users who are consuming the reports they can authenticate using their credentials and view the data, Data will publish to cloud environment using this option.

#### On Premises data sources

like ( Flat file, SQL Server , Oracle, SAP etc) if you build power BI report using these data sources required gateway connection to refresh the datasets in power BI service to see the update data in report level using enterprise gateway connection we can maintain our data securely and it will act as interface between data source to Power BI Service

We have two types option available in data source connectors (if your using SQL Server\oracle\SAP) 

#### Import Query 

Import Query option(It works as Extract connection): Using this option we can import 1 GB data to Power BI Data model(Power BI Desktop) when we publish report to power BI service it will publish with data if you want see updated data in report then we need gateway connection to refresh report dataset.

#### Direct Query

Direct Query option (It works as Live Connection): Using this option we cannot import data to power BI Data Model (Power BI Desktop) when we publish report to power BI Service it will publish report and dataset structure. If you want, see data in report level we need to assign gateway connection to dataset then can able to see the data in report

To Know more details about Gateway connection click [here](https://docs.microsoft.com/en-us/power-bi/connect-data/service-gateway-onprem)
To Know more details about Import and Direct query Options click [here](https://docs.microsoft.com/en-us/power-bi/connect-data/desktop-use-directquery)

### Power BI Mobile

Power BI offers a set of mobile apps for iOS, Android, and Windows 10 mobile devices. In the mobile apps, you can connect to reports and interact with your cloud and on-premises data.
You create reports in Power BI Desktop. You create dashboards, and view dashboards and reports in the Power BI report service (https://powerbi.com). You view on-premises Power BI reports on Power BI Report Server. All these reports and dashboards are available in the Power BI mobile apps, whether they're on premises or in the cloud. Try viewing and interacting with them on your mobile device, be it iOS (iPad, iPhone, iPod Touch, or Apple Watch), Android phone or tablet, or Windows 10 device.

![Powerbimobile](./img/Powerbimobile.png)

In a Venn diagram comparing Power BI Desktop and the Power BI service, the area in the middle shows how the two overlap. Some tasks you can do in either Power BI Desktop or the service. 
To Know more details about Power BI Mobile app click [here](https://docs.microsoft.com/en-us/power-bi/consumer/mobile/mobile-android-app-get-started)

## Difference between Power BI Desktop and Power BI Service

In a Venn diagram comparing Power BI Desktop and the Power BI service, the area in the middle shows how the two overlap. Some tasks you can do in either Power BI Desktop or the service. 
The two sides of the Venn diagram show the features that are unique to the application and the service.

![Differances](./img/Powerbidifferances.png)

## Visualizations In power BI\Types of Visualizations In power BI

Visualizations (known as visuals for short) display insights that have been discovered in the data. A Power BI report might have a single page with one visual, or it might have pages full of visuals. In the Power BI service, visuals can be pinned from reports to dashboards.
It's important to make the distinction between report designers and report consumers. If you are the person building or modifying the report, then you are a designer. Designers have edit permissions to the report and its underlying dataset. In Power BI Desktop, this means you can open the dataset in Data view and create visuals in Report view. In Power BI service, this means you can open the data set or report in the report editor in [Editing view](https://docs.microsoft.com/en-us/power-bi/consumer/end-user-reading-view). If a report or dashboard has been [shared with you](https://docs.microsoft.com/en-us/power-bi/consumer/end-user-shared-with-me) , you are a report consumer. You'll be able to view and interact with the report and its visuals, but you won't be able to make as many changes as a designer can.

There are many different visual types available directly from the Power BI Visualizations pane.

![Visualizations](./img/PowerbiVisualizations.png)

More Power BI visuals are available from the [Microsoft AppSource community site](https://appsource.microsoft.com/). In AppSource you can browse and [download](https://appsource.microsoft.com/marketplace/apps?page=1&product=power-bi-visuals) Power BI visuals provided by Microsoft and the community.
If you're new to Power BI, or need a refresher, use the links below to learn the basics of Power BI visualizations. Alternately, use our Table of Contents (along the left side of this article) to find even more helpful information.
To Know more about types of Visualization click [here](https://docs.microsoft.com/en-us/power-bi/visuals/power-bi-visualization-types-for-reports-and-q-and-a)

## Types of filters in Power BI reports

In Power BI we can create filters in two ways one is using slicer visualization and second way is add required filters in Filters Pane.
Slicer Filter: This filter will work on within the page it won’t filter the data in others pages unless use the sync slicer option in power BI Desktop.
Filter Pane : we have three type of section available in filter pane as shown below, Visualization section filter will filter the data for one visual, Filter for this page section will filter the data for all the visualizations added in that page and filter for all pages section will filter the data to entire report(All pages).

![Filters](./img/PowerbiFilters.png)

To Know more details about filters click [here](https://docs.microsoft.com/en-us/power-bi/create-reports/power-bi-report-filter-types)









