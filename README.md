# docker_exporter
Copied From https://github.com/prometheus-net/docker_exporter
Updated the reference packages to make it work.

# Docker image change
`docker run --name docker_exporter --detach --restart always --volume "/var/run/docker.sock":"/var/run/docker.sock" --publish 9417:9417 farseer/docker_exporter`
