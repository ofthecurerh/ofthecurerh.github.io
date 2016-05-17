---
title: file io
layout: default
---

<center><h2>pidstat - file_io</h2></center>
<div id="chart_1">
	<script>
        create_graph("lineChart", "timeseries", "chart_1", "io_reads_KB_sec", null, null, { csvfiles: [ "csv/file_io_io_reads_KB_sec.csv" ], threshold: 50 });
	</script>
</div>
<div id="chart_2">
	<script>
        create_graph("lineChart", "timeseries", "chart_2", "io_writes_KB_sec", null, null, { csvfiles: [ "csv/file_io_io_writes_KB_sec.csv" ], threshold: 50 });
	</script>
</div>
