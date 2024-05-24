# Kamal / Prometheus example

See: https://dev.37signals.com/kamal-prometheus/

Sample app showing how to configure [Prometheus](https://prometheus.io/) metrics with
[Yabeda](https://github.com/yabeda-rb/yabeda) and [Kamal](https://kamal-deploy.org/).

### Testing metrics locally

```sh
$ rails server
```

```sh
$ curl localhost:9394/metrics
```

### Deployment

```sh
$ kamal setup
```
