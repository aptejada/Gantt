# Gantt

<h3 align="left">References:</h3>
mermaid-js-github.io/mermaid/#/gantt

<h3 align="left">Code:</h3>

```mermaid
gantt
title Ikigai
dateFormat YYYY-MM-DD
section My PhD Roadmap
Process Application:active, des2, 2022-10-11, 1w
Review Applications:    des2,2022-10-11,1w
Send Application1: active, des4, 2022-10-12, 1d
Send Application2:active, des4, 2022-10-26, 1d

section Teaching
Prepare exam1:crit, active, 2022-10-10, 4d
Return assignments:crit, active, 2022-10-10, 4d
Consultation:crit, active, 2022-10-10, 4d
Synchronous meeting: crit, 2022-10-12, 2d
Exam MB110: crit, des1, 2022-10-17, 1d
Exam MB110: crit, des1, 2022-10-20, 1d
Exam MB111: crit, des2, 2022-10-18, 1d
Exam MB111: crit, des2, 2022-10-21, 1d

section Thesis
Generate flowcharts: 2022-10-08, 2d
Revise discussion: 2022-10-22,2d

section Scripting
Compile 16S and 18S Scripts:des1,2022-10-15,2d
Practice SQL:active, des2, 2022-10-15,2d
Practice more:active, des3, 2022-10-15
And more....:active, des4,2022-10-30
Build new project: des4, 2022-10-30
```
