---
title: system
layout: default
---

<center><h2>sar - system</h2></center>
<div id="chart_1">
  <script>
	create_graph("lineChart", "timeseries", "chart_1", "interrupts_sec", null, null, { csvfiles: [ "csv/system_interrupts_sec.csv" ] });
  </script>
</div>
<div id="chart_2">
  <script>
	create_graph("lineChart", "timeseries", "chart_2", "proc_cswch_sec", null, null, { csvfiles: [ "csv/system_proc_cswch_sec.csv" ] });
  </script>
</div>
