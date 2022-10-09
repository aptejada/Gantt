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
Review Applications:    des3,after des2,1w
Send Applications:, des4, 2022-10-10

section UP Tacloban
Prepare exam1:crit, active, 2022-10-10, 4d
Return assignments:crit, active, 2022-10-10, 4d
Consultation:crit, active, 2022-10-10, 4d
Lectures: crit, 2022-10-12, 2d

section Code
Practice SQL:active, des1, 2022-10-15,2d
Compile 16S and 18S Scripts:des2,2022-10-22,2d
Practice more:des3, 2022-10-17,5d
And more....:des4,2022-10-24,5d
```
