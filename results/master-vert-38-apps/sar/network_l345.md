---
title: network l345
layout: default
---

<center><h2>sar - network_l345</h2></center>
<div id="chart_1">
	<script>
        create_graph("lineChart", "timeseries", "chart_1", "ip", null, null, { csvfiles: [ "csv/network_l345_ip.csv" ] });
	</script>
</div>
<div id="chart_2">
	<script>
        create_graph("lineChart", "timeseries", "chart_2", "nfs_client", null, null, { csvfiles: [ "csv/network_l345_nfs_client.csv" ] });
	</script>
</div>
<div id="chart_3">
	<script>
        create_graph("lineChart", "timeseries", "chart_3", "sockets", null, null, { csvfiles: [ "csv/network_l345_sockets.csv" ] });
	</script>
</div>
<div id="chart_4">
	<script>
        create_graph("lineChart", "timeseries", "chart_4", "tcp_sockets", null, null, { csvfiles: [ "csv/network_l345_tcp_sockets.csv" ] });
	</script>
</div>
<div id="chart_5">
	<script>
        create_graph("lineChart", "timeseries", "chart_5", "udp", null, null, { csvfiles: [ "csv/network_l345_udp.csv" ] });
	</script>
</div>
