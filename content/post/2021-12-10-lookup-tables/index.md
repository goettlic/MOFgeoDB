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
description: 'All lookup tables of the MOFgeoDB'
image: ''
toc: yes
output:
  blogdown::html_page:
    keep_md: yes
weight: 100
---
# Lookup Tables
#### lut_plottype


```{=html}
<div id="htmlwidget-1083cb2ab29158c1389f" style="width:100%;height:auto;" class="datatables html-widget"></div>
<script type="application/json" data-for="htmlwidget-1083cb2ab29158c1389f">{"x":{"filter":"none","vertical":false,"data":[["1","2","3","4","5","6"],[1,2,3,4,5,6],["fs","de","exc","ps","dm","pg"],["forest  structure","dendro ecology","exclosure plot","pasture structure","dendrometer band field","polygon"],[20,80,16,2,50,null],[null,null,8,2,null,null],["Waldstrukturplots nach Jürgen in den Masterkursen","Jahrringbaumfelder zur Aggregierung der Daten, eher virtuell","Auschlussplots aus Gattern und Vergleichsplots","Vegetationsaufnahmen im Freiland oder Wiese 2m*2m","Dendrometerbandfelder zur Aggregierung der Einzelbäume, eher virtuell","unregelmäßiger Plot als Polygon"]],"container":"<table class=\"display\">\n  <thead>\n    <tr>\n      <th> <\/th>\n      <th>id<\/th>\n      <th>plottype_id<\/th>\n      <th>name<\/th>\n      <th>xlength<\/th>\n      <th>ylength<\/th>\n      <th>description<\/th>\n    <\/tr>\n  <\/thead>\n<\/table>","options":{"dom":"t","columnDefs":[{"className":"dt-right","targets":[1,4,5]},{"orderable":false,"targets":0}],"order":[],"autoWidth":false,"orderClasses":false}},"evals":[],"jsHooks":[]}</script>
```

#### lut_tree_state


```{=html}
<div id="htmlwidget-0b2e4cf4b6331a1bc63a" style="width:100%;height:auto;" class="datatables html-widget"></div>
<script type="application/json" data-for="htmlwidget-0b2e4cf4b6331a1bc63a">{"x":{"filter":"none","vertical":false,"data":[["1","2","3","4","5","6","7","8","9","10","11","12"],[2,3,5,6,7,8,11,12,13,14,15,16],["1.1","1.2","2.4","2.1","2.2","2.3","3.1","3.2","3.3","3.4","2.5","0"],[1,1,0,0,0,0,0,0,1,1,0,1],["alive","alive","dead","dead","dead","dead","felling","timber extraction","limbing","bark ringing","dead","db"],["first survey living tree","living tree from young growth","died unspecified","first survey dead tree","trunk fracture","windthrow with uprooted tree","felling only","felling and timber extraction","limbing","bark ringing","first survey stump only","first db entry"]],"container":"<table class=\"display\">\n  <thead>\n    <tr>\n      <th> <\/th>\n      <th>id<\/th>\n      <th>state_id<\/th>\n      <th>state<\/th>\n      <th>name<\/th>\n      <th>description<\/th>\n    <\/tr>\n  <\/thead>\n<\/table>","options":{"dom":"t","paging":false,"columnDefs":[{"className":"dt-right","targets":[1,3]},{"orderable":false,"targets":0}],"order":[],"autoWidth":false,"orderClasses":false}},"evals":[],"jsHooks":[]}</script>
```




