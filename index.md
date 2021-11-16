---
marp: true
theme: gaia
size: 4K
class: default
paginate: true
footer: @asm0di0 
backgroundImage: "linear-gradient(to bottom, #000 0%, #1a2028 50%, #293845 100%)"
color: white
title: Noname
---
<!--
_class: lead
_paginate: false
_footer: ""
-->

<style>
.hljs-variable { color: lightblue }
.hljs-string { color: lightgreen }
.hljs-params { color: lightpink }
</style>

# Big Data Tools:
# <!-- fit --> Fantastic Beasts and What Do They Do

Pasha Finkelshteyn, :avocado: for Big Data :computer:

---

# What is Big Data?

## Nobody knows

---

# What is Big Data?

* Doesn't fit a single node
* Scales without rearchitecturing when grows (3V)
    - Volume
    - Velocity
    - Variety
* Enough data to make reliable business decisions

---

![bg cover opacity:60%](https://source.unsplash.com/iar-afB0QQw)

<!-- _class: lead -->

# <!-- fit --> Who handles this data? Data Engineers!

---
![bg right](https://source.unsplash.com/HUyICL8qbEE)
![bg right](https://source.unsplash.com/ewxjw7Gp77Q)

# Responsbilities: Pipelines

Transfer data source → sink

Fix leaks

Data engineer is pipeliner and plumbr™ in one

---

![bg left brightness:2.0](https://source.unsplash.com/2J1l5tuuRaI)

# Responsibilities: architecture

Architecture of storage

Architecture of pipelines

Tool selection

---

![bg right](https://source.unsplash.com/zwd435-ewb4)

# Responsibilities: automation

Work together with SRE, Ops, analysts, and DS

Help in automation of chore tasks

Orchestration

---

<!--
_footer: ""
_paginate: false
-->

![bg fit](images/data2021.png)

---

# What languages DEs use?

* ![width:1em](https://upload.wikimedia.org/wikipedia/commons/c/c9/DataGrip.svg) SQL
* ![width:1em](https://upload.wikimedia.org/wikipedia/commons/1/1d/PyCharm_Icon.svg) Python
* ![width:1em](https://plugins.jetbrains.com/files/1347/145457/icon/pluginIcon.svg) Scala
* ![width:1em](https://upload.wikimedia.org/wikipedia/commons/9/9c/IntelliJ_IDEA_Icon.svg) Java
* ![width:1em](https://plugins.jetbrains.com/files/6632/141860/icon/pluginIcon.svg) R

---

# What languages DEs use?

- ![width:1em](https://upload.wikimedia.org/wikipedia/commons/c/c9/DataGrip.svg) SQL
- ![width:1em](https://upload.wikimedia.org/wikipedia/commons/1/1d/PyCharm_Icon.svg) Python
- ![width:1em](https://plugins.jetbrains.com/files/1347/145457/icon/pluginIcon.svg) Scala
- ![width:1em](https://upload.wikimedia.org/wikipedia/commons/9/9c/IntelliJ_IDEA_Icon.svg) Java
- ![width:1em](https://plugins.jetbrains.com/files/6632/141860/icon/pluginIcon.svg) R

:fireworks: folks, we cover all major languages DEs use!

---

# What languages DEs use?

But also… NoCode/LowCode tools!

![height:2em](https://nifi.apache.org/assets/images/apache-nifi-logo.svg) ![height:2em](https://upload.wikimedia.org/wikipedia/commons/3/3f/HubSpot_Logo.svg)

![height:2em](https://fivetran.com/static-assets-website/static/fivetran-logo.fb5c1b9c.svg)

![height:2em](https://www.metabase.com/images/logo.svg) ![height:2em](https://assets-global.website-files.com/5d9bd68c0f53874617f2081b/60661f88ff8419d348967a8b_Parabola%20Blue.svg)

And many more

---

# NoCode is so popular that…

![bg right:25% fit](https://s.asm0dey.ru/iQ57H/qr-code?size=310&format=svg&errorCorrection=L)

At [![height:.8em](https://smartdataconf.ru/img/conference/smartdata/logo/white.svg)](https://smartdataconf.ru/en/)* conference we had a separate talk on hardcore vs "casual" DEs

<small>* I'm humble member of PC</small>

---

<!-- 
_class: lead
 -->


# <!-- fit --> What do fantastic beasts from BDT team do?

![](https://i.imgflip.com/5ue46q.jpg)

---

# <!-- fit --> What do fantastic beasts from BDT team do?

![bg right:30%](https://source.unsplash.com/KnhFefEXLlU)

We integrate all the tools we can inside our plugin.

Currently they are:

![height:2em](https://uploads-ssl.webflow.com/5e724862760345325327026c/5fa7238e9ad1b43af56de907_apache-spark-white-logo-p-800.png) ![height:2em](https://zeppelin.apache.org/assets/themes/zeppelin/img/zeppelin_svg_logo.svg) ![height:2em](https://svn.apache.org/repos/asf/kafka/site/logos/originals/png/WIDE%20-%20White%20on%20Transparent.png) ![height:2em](https://cloud-elements.com/wp-content/uploads/2020/03/azure-blob-storage.png) ![height:2em](images/cloud_storage.svg) ![height:2em](https://upload.wikimedia.org/wikipedia/commons/b/bc/Amazon-S3-Logo.svg) ![height:2em](images/emr.svg) and more

Why these :arrow_up:? We believe they're widely used!

---

# Supported functionalities

* Remote (and Local) file systems
* Binary formats view
* Notebook support
* Monitoring support

---

# Remote (and Local) file systems

- Copy-paste
- Rename
- Drag&Drop
- Metainfo show

---

# Binary formats view

- avro
- orc
- parquet

---

# Notebook support

- Zeppelin
- DataBricks (never released)

Why do we need notebook support?

- Autocompletion
- Refactoring

---

# Monitoring support

- Spark
- Hadoop
- Kafka

---

<!-- 
_class: lead
 -->

# Kafka

Kafka is WIP, will be released soon.

We've added **producers** and **consumers**
