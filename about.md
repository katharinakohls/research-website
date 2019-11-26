---
title: About
layout: default
order: 4
---

<ul class="nav-ul">
    {% for link in site.data.navigation %}
    <li class="nav-li"><a href="{{ link.url }}">{{ link.title }}</a></li>
    {% endfor %}
</ul>

# About
I am a postdoctoral researcher at the [Systems Security Chair](https://www.syssec.ruhr-uni-bochum.de/chair/) of the Ruhr University Bochum within the excellence cluster for Cyber Security in the Age of Large-Scale Adversaries [CASA](https://casa.rub.de/en.html).  

My research focuses on information leaks in privacy enhancing technologies. One example of this is Tor, where the persisting threat of traffic analysis attacks remains and open issue and motivates research on new offensive and defensive techniques. Besides dedicated anonymity systems, I am also interested in the consequences of transferring well-known attacks to new contexts like LTE.

 <img src="_data/kk.jpg" alt="kk" style="width:500px;height:600px;"> 
