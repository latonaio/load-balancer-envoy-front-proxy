FROM latonaio/envoy:latest

COPY envoy-front.yaml /etc/envoy-front.yaml

CMD /usr/local/bin/envoy -c /etc/envoy-front.yaml --base-id 1