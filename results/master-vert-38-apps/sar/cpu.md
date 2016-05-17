---
title: cpu
layout: default
---

<center><h2>sar - cpu</h2></center>
<div id="chart_1">
	<script>
        create_graph("stackedAreaChart", "timeseries", "chart_1", "all_cpu_busy", null, null, { csvfiles: [ "csv/cpu_all_cpu_busy.csv" ] });
	</script>
</div>
<div id="chart_2">
	<script>
        create_graph("lineChart", "timeseries", "chart_2", "frequency_MHz", null, null, { csvfiles: [ "csv/cpu_frequency_MHz.csv" ] });
	</script>
</div>
