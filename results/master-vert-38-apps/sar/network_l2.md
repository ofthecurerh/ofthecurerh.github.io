---
title: network l2
layout: default
---

<center><h2>sar - network_l2</h2></center>
<div id="chart_1">
	<script>
        create_graph("lineChart", "timeseries", "chart_1", "network_Mbits_sec", null, null, { csvfiles: [ "csv/network_l2_network_Mbits_sec.csv" ], threshold: 1 });
	</script>
</div>
<div id="chart_2">
	<script>
        create_graph("lineChart", "timeseries", "chart_2", "network_packets_sec", null, null, { csvfiles: [ "csv/network_l2_network_packets_sec.csv" ], threshold: 300 });
	</script>
</div>
