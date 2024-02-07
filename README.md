# Traceroute_with_graph_output
Python3 wrapper around traceroute is written, so that you can programmatically run traceroute multiple times, read the latency statistics output by every run, and build a distribution of latency values over which to compute the required statistics.
For instance, the main output of your program should be a file in JSON format that looks like this example:

[{'avg': 0.645,
  'hop': 1,
  'hosts': [['172.17.0.1', '(172.17.0.1)']],
  'max': 2.441,
  'med': 0.556,
  'min': 0.013},
 {'avg': 6.386,
  'hop': 2,
  'hosts': [['testwifi.here', '(192.168.86.1)']],
  'max': 16.085,
  'med': 5.385,
  'min': 3.108},
 {'avg': 26.045}
