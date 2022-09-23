# Dapr pub/sub demo

I'm just using this repo to host a simple Kubernetes YAML that deploys a couple of Dapr pub/sub apps. One publishes some random temperature data and the other one subscribes to it, and publishes to a different topic if the the value is over a certain threshold. The point of the YAML is that you can change the threshold in the YAML and, through GitOps, the Dapr apps would adopt the updates.
