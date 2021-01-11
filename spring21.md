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
    - [Lightning Email Template](emailtemp)

- Reports and Dashboards
    - [Save Dashboard Results with Filter URL Parameters](#filterurl)
    - [Multi-Field Selection in Reports](#mfrpts)

- Document processing
    - [Einstein OCR to detect (beta)](#eocr)

<a name="customactions"></a>
### Pre Spring 21
![pre Spring 21](img/pre-s21-case-1.gif)
### Spring 21

![Spring 21](img/s21-case-1.gif) 


### References
- [Power Up Recently Viewed Lists with Customizable Actions](https://help.salesforce.com/articleView?id=release-notes.rn_lex_mru_list_actions.htm&type=5&release=230)


<a name="manualsharing"></a>
## Share Records with Manual Sharing 
- Now you can share records and manage record shares in a new streamlined interface.
    - Previously, you need to switch to Salesforce Classic to give specific users and user groups access to records.

### Pre Spring 21
![manual sharing pre](img/mshare-1.png) 

### Spring 21
![manual sharing s21-2](img/mshare-21-1.png) 
![manual sharing s21](img/mshare-21-2.png) 

<a name="fhelplimit"></a>
## Field-Level Help Text limit: 255 to 510 chars
![fhelp 510](img/fhelp-510-1.png)

### References
[Define Field-Level Help](https://help.salesforce.com/articleView?id=customhelp_defining_field_level_help.htm&type=5)



<a name="dupcatch"></a>
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
<a name="dynaactions"></a>
![dyna actions-1](img/dya-actions-01.png)
![dyna actions-2](img/dyna-actions-21.png )

### References
- [Salesforce Dynamic Actions - How Salesforce Administrators Can Easily Control Visibility of Actions](https://www.youtube.com/watch?v=AE1J5JSdpdc&list=PLrC_ei2_Pv0Gb-uuA5UxFneaVSjkCepYQ)

<a name="page-perf-1.png"></a>
## Page Performance analyze

![page perf](img/page-perf-1.png)
![page perf2](img/page-perf-2.png)


<a name="iag"></a>
## In-App-Guidance
![iag-1](img/iag-1.png)
![iag-2](img/iag-2.png)
![iag-3](img/iag-3.png)
![iag-4](img/iag-4.png)
![iag-5](img/iag-5.png)


<a name="msteams"></a>
## MS Teams Integration - Pilot
![MS Team](img/msteams-pilot-1.png)


<a name="ow-email"></a>
## Org Wide Email setup
![ow-e-1](img/ow-email-1.png)
![ow-e-2](img/ow-email-2.png)

<a name="emailtemp"></a>
## Lightning Email Template
- ![Email template-1](img/email-templ-1.png)
- ![Email template-2](img/email-templ-2.png)


<a name="filterurl"></a>
## Save Dashboard Results with Filter URL Parameters

![Dashboard - filter url]( https://resources.docs.salesforce.com/images/38f9b0a20cabda8dd84f5921ae742525.png)
-  Create a custom URL that includes the filter parameters. Then when you access the URL, your dashboard opens with the filters already set.

### References
- [Save Dashboard Results with Filter URL Parameters](https://help.salesforce.com/articleView?id=release-notes.rn_rd_dashboards_filter_url.htm&type=5&release=230)

<a name="mfrpts"></a>
## Multi-Field Selection in Reports]
- You can drag multiple fields to your reports with a single action. 
![rpt mf](img/ept-mf-1.png)
![mfrpts](https://resources.docs.salesforce.com/images/fb63a482d2bdf3ccfa51e990145f175f.png)

## References
- [Streamline Report Creation with Multi-Field Selection](https://help.salesforce.com/articleView?id=release-notes.rn_rd_reports_multifield_select.htm&type=5&release=230)


<a name="eocr"></a>
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

## Links
-  Spring21 Release Webinar for Enterprise Customers [SP]
    - [Video](https://salesforce.vidyard.com/watch/Bb5KtxUUvvm5xfdpThuxHG)
    - [Slides]( https://sfdc.co/cdXukP)
 
