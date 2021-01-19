# Starting a dataflow job in Slack 

## Topics
- [Desktop](#desktop)
- [Mobile](#mobile)
- [DX](#dx)

- [Monitor](#monitor)

<a name="desktop"></a>
## Demo (desktop)
![demo-myEA](img/myEA-1.gif)


<a name="mobile"></a>
## Screenshots (Mobile)

<table>
<tr>
<td> <img src='img/myEA-1.PNG' width='300'/></td>
<td><img src='img/myEA-2.PNG' width='300'/></td>
<td><img src='img/myEA-3.png' width='300'/></td>
</table>

<a name="monitor"></a>
## Monitor
![monitor-desktop](img/myEA-moinitor-1.png)

<img src='img/myEA-moinitor-2.png' width='300'/>

<a name="dx"></a>
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
