---
title: cpu usage
layout: default
---

<center><h2>pidstat - cpu_usage</h2></center>
<div id="chart_1">
	<script>
        create_graph("stackedAreaChart", "timeseries", "chart_1", "percent_cpu", null, null, { csvfiles: [ "csv/cpu_usage_percent_cpu.csv" ], threshold: 1 });
	</script>
</div>
