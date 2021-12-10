---
title: Lookup Tables
author: goettlic
date: '2021-12-10'
slug: []
categories:
  - mofgeodb
tags:
  - database
subtitle: ''
description: ''
image: ''
toc: yes
output:
  blogdown::html_page:
    keep_md: yes
weight: 100
---
# Lookup Tables
#### lut_plottype
<!-- und auch hier besser tabelle aus db direkt auslesen mit anzahl o.ä.-->
plottype_id | name | xLength | yLength | description
------------|------|---------|---------|-------------
fs | forest structure | 20.0 | NULL | Waldstrukturplots nach Jürgen in den Masterkursen
de | dendro ecology | 80.0 | NULL | Jahrringbaumfelder zur Aggregierung der Daten, eher virtuell
exc | exclosure plot | 16.0 | 8.0 | Auschlussplots aus Gattern und Vergleichsplots
ps | pasture structure | 2.0 | 2.0 | Vegetationsaufnahmen im Freiland oder Wiese 2m*2m
dm | dendrometer band field | 50.0 | NULL | Dendrometerbandfelder zur Aggregierung der Einzelbäume, eher virtuell
pg | polygon | NULL | NULL | unregelmäßiger Plot als Polygon
sub | subplot | NULL | NULL | Subplot als regelmäßige Unterteilung eines größeren Plots 

#### lut_tree_state
<!-- eigentlich besser direkt aus der db lesen und die Tabelle anzeigen lassen -->
state_id | state | name | description
---------|-------|------|----------------
1.1 | 1 |	alive |	first survey living tree
1.2 |	1 |	alive |	living tree from young growth
2.4 |	0 |	dead |	died unspecified
2.1 |	0 |	dead |	first survey dead tree
2.2 |	0 |	dead |	trunk fracture
2.3 |	0 |	dead |	windthrow with uprooted tree
3.1 |	0 |	felling |	felling only
3.2 |	0 |	timber extraction |	felling and timber extraction
3.3 |	1 |	limbing |	limbing
3.4 |	1 |	bark ringing |	bark ringing
2.5 |	0 |	dead |	first survey stump only
0 |	1 |	db | first db entry
