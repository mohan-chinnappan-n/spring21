# Spring 21 Release


## Topics
- UI
    - [Showing Custom Actions button in the **Recently Viewed List**](#customactions)
    - [Share Records with Manual Sharing](#manualsharing)
    - [Field-Level Help Text limit: 255 to 510 chars](#fhelplimit)
    - [Catch Potential Duplicates Before Saving](#dupcatch)
    - [Dynamic actions](#dynaactions)
- Performance
    - [Page performance analyze](#pageperf)
- Adoption 
    - [In-App-guidance](#iag)

- Communications
    - [MS Teams Integration - Pilot](#msteams)
    - [Org Wide Email setup](#ow-email)
    - [Lightning Email Template](#emailtemp)

- Reports and Dashboards
    - [Save Dashboard Results with Filter URL Parameters](#filterurl)
    - [Multi-Field Selection in Reports](#mfrpts)
    - [Report export into xlsx](#rxlsx)

- Document processing
    - [Einstein OCR to detect (beta)](#eocr)

- [**FSC**](https://help.salesforce.com/articleView?id=release-notes.rn_fsc.htm&type=5&release=230)
    - [Interaction Summaries](#intersum)
    - Rollups
        - [Perform Rollup-by-Lookup Calculations Faster with Data Processing Engine](#rbl3)
        - [Use the Record Rollup Optimization org preference to improve record rollup performance](#recru)
    - Data model
        - [New and Changed Financial Services Cloud Object Fields](https://help.salesforce.com/articleView?id=release-notes.rn_fsc_changed_objects.htm&type=5&release=230)
    - Data Capture
        - [Automate Financial Data Capture Using Mappings](https://help.salesforce.com/articleView?id=release-notes.rn_fsc_intelligent_form_reader_mappings.htm&type=5&release=230)
        - [Extract Information from Uploaded Documents](#extractOCR)
    - Data Capture
        -[Compliant Data Sharing](https://help.salesforce.com/articleView?id=release-notes.rn_fsc_compliant_data_sharing.htm&type=5&release=230)

    - Management
        - [Branch Management](https://help.salesforce.com/articleView?id=release-notes.rn_fsc_branch.htm&type=5&release=230)
    - UI
        - [ACR](https://help.salesforce.com/articleView?id=release-notes.rn_fsc_arc.htm&type=5&release=230)
    - Mobile-Enabled Components
        - [Stay Productive with More Financial Services Cloud Lightning Components for Mobile](https://help.salesforce.com/articleView?id=release-notes.rn_fsc_mobile_components.htm&type=5&release=230)


    - Client Engagement
        -  To help drive client engagement, the Analytics for Wealth Management app now includes person life event data that you can aggregate into groups. Life events can include occasions such as birthdays or retirement. For example, you can create a marketing campaign for clients near retirement age or send greetings to clients who are recently married.
            - [Drive Client Engagement with Life Event Insights](https://help.salesforce.com/articleView?id=release-notes.rn_fsc_analytics_life_event_dataset.htm&type=5&release=230)

- [**EA - Tableau CRM**](https://help.salesforce.com/articleView?id=release-notes.rn_bi_analytics_cloud.htm&type=5&release=230)
    - Data Integration and Preparation
        - [Sync Out : SF -> Snowflake : Keep Salesforce Data Fresh in Snowflake](#synchoutSnow)
        - [Export Datasets to .csv with the Data Prep Output Node](#exportcsv)
        - [Merge Prepared Tableau CRM Data into Salesforce with the Salesforce Output Connector (Beta)](#sfout)
        - Tighter Security Encryption Requirements for Connected Data Sources
            - TLS protocol version 1.2 is enforced for all connections. Source systems that use TLS v1.1 or below can’t connect until you reconfigure them.
        - [Sharing Inheritance Coverage Assessment](#easharing)
        - [ Smart Transform Pilot Program](https://help.salesforce.com/articleView?id=release-notes.rn_bi_integrate_smarttransformpilot.htm&type=5&release=230)
            -  Time Series Forecasting transformation, Cluster transformation, and pivot functionality in the Aggregate node.
        - [Anticipate the Future with Time Series Forecasting (Pilot)](https://help.salesforce.com/articleView?id=release-notes.rn_bi_integrate_transformation_timeseriesforecasting.htm&type=5&release=230)
            - Predict measure values based on historical data  and seasonlity
            ![time series forecasting](https://resources.docs.salesforce.com/images/8c5d478b8af921f16618d6c7ecffd729.png)
        - [Clean Up Your Data by Standardizing Column Value Formats](https://help.salesforce.com/articleView?id=release-notes.rn_bi_integrate_transformation_editattributes.htm&type=5&release=230)
            - ![col transfrom](https://resources.docs.salesforce.com/images/a3d3ba315a35d9f1ea26ad16850dd7ec.png)
            - ![col transform2](https://resources.docs.salesforce.com/images/6eeab56509e2e780f8cc54a24b9e7934.png)

    - [App Building](https://help.salesforce.com/articleView?id=release-notes.rn_bi_app_building.htm&type=5&release=230)
        - [Take Action Anywhere on Any Data on up to 100 Records at Once](#takeactions)
        - [Use SQL with Tableau CRM Direct Data (Beta)](https://help.salesforce.com/articleView?id=release-notes.rn_bi_directdata_sql.htm&type=5&release=230)
            - Run SQL queries on live datasets
            - Setup > Analytics > [Enable SQL for live datasets (Beta] > [Save]
            ![sql mode](https://resources.docs.salesforce.com/images/44e719aae5b723c512eeb0f2e65d9bc6.png)
        - Group Data by up to Six Fields in Explorer
            - You can now group your data by up to six dimensions or date fields in explorer charts and tables. 
                -  Previously, you edited SAQL queries or JSON files to include more than four groupings for your data.










<a name="customactions"></a>  [TOPICS](#topics)
### Pre Spring 21
![pre Spring 21](img/pre-s21-case-1.gif)
### Spring 21

![Spring 21](img/s21-case-1.gif) 


### References
- [Power Up Recently Viewed Lists with Customizable Actions](https://help.salesforce.com/articleView?id=release-notes.rn_lex_mru_list_actions.htm&type=5&release=230)


<a name="manualsharing"></a>  [TOPICS](#topics)
## Share Records with Manual Sharing 
- Now you can share records and manage record shares in a new streamlined interface.
    - Previously, you need to switch to Salesforce Classic to give specific users and user groups access to records.

### Pre Spring 21
![manual sharing pre](img/mshare-1.png) 

### Spring 21
![manual sharing s21-2](img/mshare-21-1.png) 
![manual sharing s21](img/mshare-21-2.png) 

<a name="fhelplimit"></a>  [TOPICS](#topics)
## Field-Level Help Text limit: 255 to 510 chars
![fhelp 510](img/fhelp-510-1.png)

### References
[Define Field-Level Help](https://help.salesforce.com/articleView?id=customhelp_defining_field_level_help.htm&type=5)



<a name="dupcatch"></a>  [TOPICS](#topics)
## Catch Potential Duplicates Before Saving

![dyna forms](img/dynamic-forms-1.png)
![dyna forms msg](img/dynamic-forms-2.png)

![dya forms](img/dyna-forms-0.gif)
![dya forms](img/dyna-forms-1.gif)
- Custom Objects for now

### References
- [Catch Potential Duplicates Before Saving](https://help.salesforce.com/articleView?id=release-notes.rn_lex_duplicates.htm&type=5&release=230)
- [Dynamic Forms](https://help.salesforce.com/articleView?id=dynamic_forms_migrate.htm&type=5)

## Dynamic Actions - How Salesforce Administrators Can Easily Control Visibility of Actions
- Beta to GA
<a name="dynaactions"></a>  [TOPICS](#topics)
![dyna actions-1](img/dya-actions-01.png)
![dyna actions-2](img/dyna-actions-21.png )

### References
- [Salesforce Dynamic Actions - How Salesforce Administrators Can Easily Control Visibility of Actions](https://www.youtube.com/watch?v=AE1J5JSdpdc&list=PLrC_ei2_Pv0Gb-uuA5UxFneaVSjkCepYQ)

<a name="pageperf"></a>  [TOPICS](#topics)
## Page Performance analyze

![page perf](img/page-perf-1.png)
![page perf2](img/page-perf-2.png)


<a name="iag"></a>  [TOPICS](#topics)
## In-App-Guidance
![iag-1](img/iag-1.png)
![iag-2](img/iag-2.png)
![iag-3](img/iag-3.png)
![iag-4](img/iag-4.png)
![iag-5](img/iag-5.png)


<a name="msteams"></a>  [TOPICS](#topics)
## MS Teams Integration - Pilot
![MS Team](img/msteams-pilot-1.png)


<a name="ow-email"></a>  [TOPICS](#topics)
## Org Wide Email setup
![ow-e-1](img/ow-email-1.png)
![ow-e-2](img/ow-email-2.png)

<a name="emailtemp"></a>  [TOPICS](#topics)
## Lightning Email Template
- ![Email template-1](img/email-templ-1.png)
- ![Email template-2](img/email-templ-2.png)


<a name="filterurl"></a>  [TOPICS](#topics)
## Save Dashboard Results with Filter URL Parameters

![Dashboard - filter url]( https://resources.docs.salesforce.com/images/38f9b0a20cabda8dd84f5921ae742525.png)
-  Create a custom URL that includes the filter parameters. Then when you access the URL, your dashboard opens with the filters already set.

### References
- [Save Dashboard Results with Filter URL Parameters](https://help.salesforce.com/articleView?id=release-notes.rn_rd_dashboards_filter_url.htm&type=5&release=230)

<a name="mfrpts"></a>  [TOPICS](#topics)
## Multi-Field Selection in Reports]
- You can drag multiple fields to your reports with a single action. 
![rpt mf](img/rept-mf-1.png)
![mfrpts](https://resources.docs.salesforce.com/images/fb63a482d2bdf3ccfa51e990145f175f.png)

## References
- [Streamline Report Creation with Multi-Field Selection](https://help.salesforce.com/articleView?id=release-notes.rn_rd_reports_multifield_select.htm&type=5&release=230)

<a name="rxlsx"></a> [TOPICS](#topics)
## Report export into xlsx

![rept export](img/rept-export-1.png)
![report export](https://resources.docs.salesforce.com/images/a291dc3a99044585ceebad9a12d24a34.png)

## Resources
- [Get Report Details Emailed in .xlsx Format](https://help.salesforce.com/articleView?id=release-notes.rn_rd_reports_details_email.htm&type=5&release=230)


<a name="eocr"></a>  [TOPICS](#topics)
## Einstein OCR to Detect Text in PDFs (Beta)
```
curl -X POST -H "Authorization: Bearer <TOKEN>"\
             -F sampleLocation="https://www.cloudkicks.com/annual_report.pdf"\
             -F task="text"\
             -F modelId="OCRModel"\
             https://api.einstein.ai/v2/vision/ocr

```

### References 
- [Use Einstein OCR to Detect Text in PDFs (Beta)](https://help.salesforce.com/articleView?id=release-notes.rn_einstein_vision_ocr_pdf_support.htm&type=5&release=230)
- [What is Einstein OCR?](https://metamind.readme.io/docs/what-is-einstein-ocr)

<a name="itersum"></a>  [TOPICS](#topics)
##  FSC -  Interaction Summaries
- Structured notes of client or partner interactions and share them with stakeholders in a compliant manner with the new Interaction Summaries feature.
- Help financial advisors build and deepen customer relationships with the new Interaction Summaries data model. They can manage every aspect of client and partner interactions and take advantage of structured note-taking and compliant, role-based data sharing options
- Financial advisors can take detailed meeting notes, specify the confidentiality level of the notes, and add action items or next steps. 

![is1](https://resources.docs.salesforce.com/images/eeca8e0b178442a8f98bf44a7553b1a7.png)
![is2](https://resources.docs.salesforce.com/images/ea4e8860abd7f033dbddea99b8ca20c1.png)
![is3](https://resources.docs.salesforce.com/images/fcb2d59e16c07e5277703fceea782579.png)

### References 
- [Capture and Share Meeting Notes with Interaction Summaries](https://help.salesforce.com/articleView?id=release-notes.rn_fsc_interaction_summary.htm&type=5&release=230)



<a name="rbl3"></a>  [TOPICS](#topics)
## Perform Rollup-by-Lookup Calculations Faster with Data Processing Engine
- Uses the superior processing power of Tableau CRM for faster calculations of RBL rules. The new RBL framework lets you convert your existing RBL rules into Data Processing Engine definitions. The high-performance Data Processing Engine definitions significantly reduce the processing time to aggregate financial information. In Data Processing Engine, you have greater flexibility when defining or modifying RBL rules. For example, you can add multiple data sources, define joins and appends, and add formulas to your rules.
### References 
- [Perform Rollup-by-Lookup Calculations Faster with Data Processing Engine](https://help.salesforce.com/articleView?id=release-notes.rn_fsc_rbl_dpe.htm&type=5&release=230)



![rbl3](https://resources.docs.salesforce.com/images/3ea2f43a64a81ede7a5ea2e3ff8365e3.png)
![rbl32](img/rbl3-1.png)

<a name="recru"></a>  [TOPICS](#topics)
## Use the Record Rollup Optimization org preference to improve record rollup performance

![rup settings](img/fsc-rollup-settings-1.png)

<a name="extractOCR"></a>  [TOPICS](#topics)
##  Extract Information from Uploaded Documents
- Accelerate document-driven business processes by using optical character recognition (OCR) technology to extract fields from documents uploaded by borrowers, partners, or loan officers. Any Salesforce process that uses document checklist items can use this new Intelligent Form Reader capability

<a name="synchoutSnow"></a>  [TOPICS](#topics)
## Sync Out : SF -> Snowflake : Keep Salesforce Data Fresh in Snowflake
 - Keep your Salesforce data up to date in Snowflake without the need for a third-party ETL tool.
![Sync out1](https://resources.docs.salesforce.com/images/fdec61a25028c29858e52a68c9513d18.png)
![Sync out2](https://resources.docs.salesforce.com/images/48fc9eed865004f9859a9cdc85c21787.png)

<a name="exportcsv"></a>  [TOPICS](#topics)
## Export Datasets to .csv with the Data Prep Output Node
- Use the Data Prep output node to save your prepared data from Tableau CRM as a data and schema file. Then you can download the data locally using the public API as a .csv file. 
- This data push lets you transfer augmented, cleaned, and improved data from Tableau CRM into your external systems for analysis, storage, or to inform business processes. For example, export a dataset from Tableau CRM, then download it locally to explore in Microsoft Excel.

- Build your recipe with Data Prep. In an Output node, select to write to CSV (1). Enter the name (2) of the user who downloads the file. Optionally, specify the maximum file size and maximum number of rows per partition of the CSV file (3).
![Csv download](https://resources.docs.salesforce.com/images/379fbe8cc783b8d742ac3a46510a809a.png)
- Save the recipe. When the recipe runs, Tableau CRM writes the output to the Salesforce database.

### References
- [Export your Einstein Analytics datasets](https://www.salesforceblogger.com/2020/08/19/export-your-einstein-analytics-datasets/)
- [Export Datasets to .csv with the Data Prep Output Node](https://help.salesforce.com/articleView?id=release-notes.rn_bi_integrate_output_csv.htm&type=5&release=230)

<a name="sfout"></a>  [TOPICS](#topics)
## Merge Prepared Tableau CRM Data into Salesforce with the Salesforce Output Connector (Beta)
-  On the Connect tab of the Data Manager, click Connect to Data. Add a connection on the Output Connections tab and configure it with a Salesforce org’s information. The org credentials you use determine the connector’s access level.

![sfout 1](https://resources.docs.salesforce.com/images/17cacd04ec6556d8daf5bf531ac454bf.png)
- Build your recipe with Data Prep. In our example, look up and update Salesforce account data with external order data. 
    - In an Output node, select to write to the Output Connection (1). 
    - Select the **Salesforce Output connection** to push data to (2) and the object to write to (3). 
    - Select whether you want the push to UPDATE, INSERT, or UPSERT data (4). 
    - Map recipe columns to their equivalent external object columns (5).

![sfout 2](https://resources.docs.salesforce.com/images/9d2a35d288d12b766b53c76f5eda6df6.png)
- Save the recipe. When the recipe runs, Tableau CRM writes the output to the Salesforce org.

<a name="easharing"></a>  [TOPICS](#topics)
## Sharing Inheritance Coverage Assessment
- Easily determine which objects and users are good candidates for Sharing Inheritance with the improved Sharing Inheritance Coverage Assessment
- Sharing inheritance lets Tableau CRM apply the same sharing setup for your datasets as Salesforce uses for your objects. 
![sharing inherit](https://resources.docs.salesforce.com/images/32015c79c3715fe142a228be07c66e87.png)
- A sharing descriptor is the ID of the user or group that has access to the record

### References
- [Merge Prepared Tableau CRM Data into Salesforce with the Salesforce Output Connector (Beta)](https://help.salesforce.com/articleView?id=release-notes.rn_bi_integrate_salesforce_output_beta.htm&type=5&release=230)

<a name="takeactions"></a>
## Take Action Anywhere on Any Data on up to 100 Records at Once
- To add a custom action menu to a dimension column in Explorer, click the column action menu for the dimension, and select Configure Actions.
    ![actions](https://resources.docs.salesforce.com/images/f5a06f4c1cd5e55d41884a047e92a704.png)
- Configure the actions for the dimension, selecting the ID, display fields, and the actions. Then click Done and save your lens.
    - ![config](https://resources.docs.salesforce.com/images/8f8c158e96c1478232f8de64ad5961cb.png)
- Next, enable your dashboard users to take quick action on up to 100 records in the configured column at the same time by adding mass quick actions. Add a values table (1) with actionable data, a faceted chart or filter (2), and a link widget (3) to your dashboard. In the widget properties panel for the link widget, name your link with text that matches the quick action (4). Select Mass Action in the Link To list (5). Select the name of the table query in the step list (6). Select the column name to apply the mass quick action to in the Action Column list (7). Then select the mass quick action to perform in the Salesforce Actions list (8)
    - ![actions2](https://resources.docs.salesforce.com/images/7aa38c8ecd0f8f7e7e3a64cb53734902.png)
- In this example, the mass quick action is to update accounts. When the user selects an account type in the faceted chart and then clicks the Update Account link, they can update all the accounts of that type, up to 100 records, using the account ID from the table query.



## Links
-  Spring21 Release Webinar for Enterprise Customers [SP]
    - [Video](https://salesforce.vidyard.com/watch/Bb5KtxUUvvm5xfdpThuxHG)
    - [Slides]( https://sfdc.co/cdXukP)
 
