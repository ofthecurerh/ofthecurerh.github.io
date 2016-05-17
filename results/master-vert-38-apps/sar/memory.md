---
title: memory
layout: default
---

<center><h2>sar - memory</h2></center>
<div id="chart_1">
	<script>
        create_graph("lineChart", "timeseries", "chart_1", "memory_activity", null, null, { csvfiles: [ "csv/memory_memory_activity.csv" ] });
	</script>
</div>
<div id="chart_2">
	<script>
        create_graph("lineChart", "timeseries", "chart_2", "memory_usage", null, null, { csvfiles: [ "csv/memory_memory_usage.csv" ] });
	</script>
</div>
