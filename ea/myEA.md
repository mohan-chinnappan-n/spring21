# Starting a dataflow job and monitor dataflow jobs using Slack 


## Topics
- [Setup](#setup)
- [Help](#help)


- [Desktop](#desktop)
    - [Demo 1](#demo1)
    - [Demo 2](#demo2)
    - [Demo 3](#demo3)



- [Mobile](#mobile)

- [Monitor](#monitor)
- [Dataflow job](#dfjob)

- [DX](#dx)


<a name="setup"></a>
## Setup
- [Url to start](https://mohansun-myea.herokuapp.com/add.html)
- https://mohansun-myea.herokuapp.com/add.html

![myEA setup](img/myEA-setup-1.gif)


<a name="help"></a>
## Help Command
<img src='img/help-1.png' width='400'/></td>


<a name="desktop"></a>
<a name="demo1"></a>
## Demo 1 (desktop)
![demo-myEA](img/myEA-1.gif)

<a name="demo2"></a>
## Demo 2
![demo-myEA2](img/myEA-2.gif)

<a name="demo3"></a>
## Demo 3
![demo-myEA3](img/myEA-demo-3.gif)



<a name="mobile"></a>
## Screenshots (Mobile)

<table>
<tr>
<td> <img src='img/myea-1.png' width='300'/></td>
<td><img src='img/myEA-2.PNG' width='300'/></td>
<td><img src='img/myEA-3.png' width='300'/></td>
</table>

<a name="monitor"></a>
## Monitor
![monitor-desktop](img/myEA-moinitor-1.png)

<img src='img/myEA-moinitor-2.png' width='300'/>

<a name="dfjob"></a>
## Dataflow Job
![dfjob1](img/myEA-dfjob-1.gif)

<a name="dx"></a>
## Using DX
```
$ sfdx mohanc:ea:dataflow:list -u mohan.chinnappan.n_ea2@gmail.com
Id,Label
02K3h000000Mr7JEAS,The_Motivator
02K3h000000Mu1oEAC,exportOppty2
02K3h000000Mu0vEAC,exportOppty
02K3h000000MtyuEAC,ExportCustomers
02K3h000000MrxWEAS,fruitsdf
02K3h000000Mr7KEAS,Default Salesforce Dataflow

```

```
$ sfdx mohanc:ea:dataflow:start -u mohan.chinnappan.n_ea2@gmail.com -i 02K3h000000MtyuEAC
Dataflow Job Id: 02K3h000000MtyuEAC
{
  id: '0303h000002AYy9AAG',
  nodesUrl: '/services/data/v50.0/wave/dataflowjobs/0303h000002AYy9AAG/nodes',
  progress: 0,
  status: 'Queued',
  syncDataflows: { dataflows: [] },
  type: 'dataflowjob',
  url: '/services/data/v50.0/wave/dataflowjobs/0303h000002AYy9AAG'
}

```

## References
- [SalesforceBlogger: Start and stop dataflows on command](https://www.salesforceblogger.com/2021/01/19/start-and-stop-dataflows-on-command/)
- [SFDX plugin for Analytics](https://www.salesforceblogger.com/2020/11/17/mohans-sfdx-plugin-for-analytics/)
