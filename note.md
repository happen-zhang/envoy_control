docker run  -v $(pwd)/baseline.yaml:/etc/envoy/envoy.yaml  --rm -p 9901:9000 -p 10000:10000 envoyproxy/envoy:v1.10.0
