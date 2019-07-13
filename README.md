# Docker jenkins-exporter devenv

Simple docker compose infrastructure/development environment for the golang training.

# Usage

Clone the project and its submodule:

```console
git clone --recursive git@github.com:abousselmi/docker-prometheus-jenkins-exporter-devenv.git
```
or

```console
git clone --recursive https://github.com/abousselmi/docker-prometheus-jenkins-exporter-devenv.git
```

Build the jenkins-exporter docker image:

```console
docker-compose build
```

Then fire it up:

```console
docker-compose up
```
or

```console
docker-compose up -d
```

Please note that the jenkins exporter container may restart multiple times. It's normal because
it is looking for the jenkins API that take few seconds to start up.

# Original projects:

  * Prometheus docker suite: https://github.com/vegasbrianc/prometheus
  * Jenkins exporter: https://github.com/lovoo/jenkins_exporter

# Licence

MIT
