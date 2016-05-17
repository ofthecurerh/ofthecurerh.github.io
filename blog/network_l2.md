---
---

<script>
var chart_1 = d3.create_graph("lineChart", "timeseries", "chart_1", "network_Mbits_sec", null, null, { csvfiles:["csv/network_l2_network_Mbits_sec.csv" ], threshold: 1 })
</script>

<script>
var chart_2 = d3.create_graph("lineChart", "timeseries", "chart_2", "network_packets_sec", null, null, { csvfiles: [ "csv/network_l2_network_packets_sec.csv" ], threshold: 300 })
</script>
