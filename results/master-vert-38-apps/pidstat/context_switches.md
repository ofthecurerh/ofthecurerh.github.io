---
title: context switches
layout: default
---

<center><h2>pidstat - context_switches</h2></center>
<div id="chart_1">
	<script>
        create_graph("lineChart", "timeseries", "chart_1", "voluntary_switches_sec", null, null, { csvfiles: [ "csv/context_switches_voluntary_switches_sec.csv" ], threshold: 100 });
	</script>
</div>
