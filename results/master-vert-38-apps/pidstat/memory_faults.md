---
title: memory faults
layout: default
---

<center><h2>pidstat - memory_faults</h2></center>
<div id="chart_1">
	<script>
        create_graph("lineChart", "timeseries", "chart_1", "minor_faults_sec", null, null, { csvfiles: [ "csv/memory_faults_minor_faults_sec.csv" ], threshold: 150 });
	</script>
</div>
