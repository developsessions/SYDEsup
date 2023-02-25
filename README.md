# SYDEsup

[![Build](https://github.com/developsessions/SYDEsup/actions/workflows/build.yml/badge.svg)](https://github.com/developsessions/SYDEsup/actions/workflows/build.yml)
[![Docker Pulls](https://badgen.net/docker/pulls/developsessions/sydesup?icon=docker&label=pulls)](https://hub.docker.com/r/developsessions/sydesup/)
[![Docker Stars](https://badgen.net/docker/stars/developsessions/sydesup?icon=docker&label=stars)](https://hub.docker.com/r/developsessions/sydesup/)
[![Docker Image Size](https://badgen.net/docker/size/developsessions/sydesup?icon=docker&label=image%20size)](https://hub.docker.com/r/developsessions/sydesup/)

SYDEsup by [STW](https://www.stw-mobile-machines.com/) is a console application for updating the STW ECUs with a Service Update Package created with the openSYDE GUI.

SYDEsup is normally delivered directly as a Windows build from STW, but sometimes its necessary to transfer the application from an Linux OS.

This is why I created this project which helps to continuous and periodically build SYDEsup for the following targets:
- Linux Debian / Ubuntu
- Alpine Linux
- Windows

The binaries are downloadable in the Releases section.

We are holding no source code here, we're pull the code from the [official repository](https://github.com/openSYDE/openSYDE).

## Docker

There are also SYDEsup [Docker](https://hub.docker.com/r/developsessions/sydesup/) images available.

Alpine Image:
```bash
sudo docker run -it developsessions/sydesup SYDEsup -h
```

Ubuntu Image:
```bash
sudo docker run -it developsessions/sydesup:ubuntu SYDEsup -h
```

---

<a href="https://www.buymeacoffee.com/developsessions" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/guidelines/download-assets-sm-1.svg" alt="Buy Me A Coffee" height="41" width="174"></a>
