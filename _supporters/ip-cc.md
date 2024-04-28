---
layout: single
permalink: /machines/ip-cc/
title: "IP-CC"
excerpt: "iRm Series"
header:
  overlay_image: /assets/images/ip2.jpg
  image: /assets/images/ip2.jpg
  teaser: assets/images/ip1.jpg
sidebar:
  nav: "machines"
---
<img class="tab-image" src="{{ site.baseurl }}/assets/images/supporter-badge.png" width="150px">

* __Producer:__ [IP-CC Coffee Roasting Machines](https://www.ip-cc.com/){:target="_blank"}, Greece
* __Machines:__ iRm Series with networked Omron or Mitshubishi PLC
* __Connection:__ MODBUS TCP via the network
* __Features:__
  - logging of environmental temperature (ET), bean temperature (BT), burner temperature, and mixer temperature
  - logging and control of airflow, drum speed and burner power
  - activation of transfer, charge and drop doors

<figure>
<center>
<a href="{{ site.baseurl }}/assets/images/buttons-IP-CC.png">
<img src="{{ site.baseurl }}/assets/images/buttons-IP-CC.png" style="width: 80%;"></a>
    <figcaption>custom event buttons</figcaption>
</center>
</figure>

### Setup

The computer running Artisan must be on the same IP network as the roaster. The default IP address of the roaster is 10.100.0.15. Configure your computer to use a static IP address in the range of the roaster (10.100.0.x) but with x different from that of the roaster (eg. 10.100.0.42). Choose 255.255.255.0 as subnet mask. 
 
This can be done on Windows using the Network Sharing Center by adding a TCP/IPv4 Local Area Connection with those properties. On macOS you set your ethernet port in the Network Control panel to "IPv4: Manually" and fill in the IP and subnet mask accordingly.

**Watch out!** Artisan doesn't monitor unsafe temperatures, so you should never leave the roaster alone.
{: .notice--primary}


<a name="EnergyRatings"></a>
## Energy Ratings

|Model|Source|Burner (kW)|
|:-----|:-----:|:-----:|
|||
| iRm_10 | LPG/NG | 45 |
| iRm_20| LPG/NG | 90 |
| iRm_35 | LPG/NG | 165 |
| iRm_70 | LPG/NG | 450 |
| iRm_140 | LPG/NG | 850 |