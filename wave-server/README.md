# Wave Server

A web server that responds with text specified in `server.message`. The statefulset is intentionally designed to take 30 seconds to start, simulating a substantial workload.

## Values.yaml

Among several best practices, a crucial one is observed here: `values.yaml` holds the base configuration, free from any specific opinions. Its primary role is to serve as documentation on how to effectively utilize the Helm chart.
