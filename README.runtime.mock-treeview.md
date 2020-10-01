# Featured Tags

* `3.1` (LTS)
  * `docker pull mcr.microsoft.com/dotnet/core/runtime:3.1`

* `5.0` (Current)
  * `docker pull mcr.microsoft.com/dotnet/core/runtime:5.0`

# About This Image

This image contains the .NET Core runtimes and libraries and is optimized for running .NET Core apps in production. This repository is limited to .NET Core 2.1 and 3.1. For .NET 5.0 and higher, see [dotnet/nightly/runtime](https://hub.docker.com/_/microsoft-dotnet-nightly-runtime/) for those versions.

Watch [dotnet/announcements](https://github.com/dotnet/announcements/labels/Docker) for Docker-related .NET announcements.

# How to Use the Image

The [.NET Core Docker samples](https://github.com/dotnet/dotnet-docker/blob/master/samples/README.md) show various ways to use .NET Core and Docker together. See [Building Docker Images for .NET Core Applications](https://docs.microsoft.com/dotnet/core/docker/building-net-docker-images) to learn more.

## Container sample: Run a simple application

You can quickly run a container with a pre-built [.NET Core Docker image](https://hub.docker.com/_/microsoft-dotnet-core-samples/), based on the [.NET Core console sample](https://github.com/dotnet/dotnet-docker/blob/master/samples/dotnetapp/README.md).

Type the following command to run a sample console application:

```console
docker run --rm mcr.microsoft.com/dotnet/core/samples
```

# Related Repos

.NET Core 2.1/3.1:

* [dotnet/core](https://hub.docker.com/_/microsoft-dotnet-core/): .NET Core
* [dotnet/core/sdk](https://hub.docker.com/_/microsoft-dotnet-core-sdk/): .NET Core SDK
* [dotnet/core/aspnet](https://hub.docker.com/_/microsoft-dotnet-core-aspnet/): ASP.NET Core Runtime
* [dotnet/core/runtime-deps](https://hub.docker.com/_/microsoft-dotnet-core-runtime-deps/): .NET Core Runtime Dependencies
* [dotnet/core/samples](https://hub.docker.com/_/microsoft-dotnet-core-samples/): .NET Core Samples
* [dotnet/core-nightly](https://hub.docker.com/_/microsoft-dotnet-core-nightly/): .NET Core (Preview)

.NET 5.0+:

* [dotnet](https://hub.docker.com/_/microsoft-dotnet/): .NET
* [dotnet/nightly](https://hub.docker.com/_/microsoft-dotnet-nightly/): .NET (Preview)

.NET Framework:

* [dotnet/framework](https://hub.docker.com/_/microsoft-dotnet-framework/): .NET Framework, ASP.NET and WCF
* [dotnet/framework/samples](https://hub.docker.com/_/microsoft-dotnet-framework-samples/): .NET Framework, ASP.NET and WCF Samples

# Full Tag Listing

| Tags | OS Version | Arch / Dockerfile | Last Modified
| -----------| -----------| -------------| -------------
| 5.0.0, 5.0, latest | Multi-platform | amd64, arm64v8, arm32v7 | 08/20/2020
| &nbsp;&nbsp;&nbsp;&nbsp;&#8627;&nbsp;&nbsp;&nbsp;5.0.0-buster-slim, 5.0-buster-slim | Debian 10 | [amd64](placeholder), [arm64v8](placeholder), [arm32v7](placeholder) | 08/20/2020
| &nbsp;&nbsp;&nbsp;&nbsp;&#8627;&nbsp;&nbsp;&nbsp;5.0.0-nanoserver-2004, 5.0-nanoserver-2004 | Windows Server, version 2004 | [amd64](placeholder) | 08/20/2020
| &nbsp;&nbsp;&nbsp;&nbsp;&#8627;&nbsp;&nbsp;&nbsp;5.0.0-nanoserver-1909, 5.0-nanoserver-1909 | Windows Server, version 1909 | [amd64](placeholder) | 08/20/2020
| &nbsp;&nbsp;&nbsp;&nbsp;&#8627;&nbsp;&nbsp;&nbsp;5.0.0-nanoserver-1903, 5.0-nanoserver-1903 | Windows Server, version 1903 | [amd64](placeholder) | 08/20/2020
| &nbsp;&nbsp;&nbsp;&nbsp;&#8627;&nbsp;&nbsp;&nbsp;5.0.0-nanoserver-1809, 5.0-nanoserver-1809 | Windows Server 2019 | [amd64](placeholder) | 08/20/2020
| 5.0.0-alpine3.12, 5.0-alpine3.12, 5.0-alpine | Alpine 3.12 | [amd64](placeholder), [arm64v8](placeholder), [arm32v7](placeholder) | 08/20/2020
| 5.0.0-focal, 5.0-focal | Ubuntu 20.04 | [amd64](placeholder), [arm64v8](placeholder), [arm32v7](placeholder) | 08/20/2020
| 3.1.7, 3.1, latest | Multi-platform | amd64, arm64v8, arm32v7 | 08/20/2020
| &nbsp;&nbsp;&nbsp;&nbsp;&#8627;&nbsp;&nbsp;&nbsp;3.1.7-buster-slim, 3.1-buster-slim | Debian 10 | [amd64](placeholder), [arm64v8](placeholder), [arm32v7](placeholder) | 08/20/2020
| &nbsp;&nbsp;&nbsp;&nbsp;&#8627;&nbsp;&nbsp;&nbsp;3.1.7-nanoserver-2004, 3.1-nanoserver-2004 | Windows Server, version 2004 | [amd64](placeholder) | 08/20/2020
| &nbsp;&nbsp;&nbsp;&nbsp;&#8627;&nbsp;&nbsp;&nbsp;3.1.7-nanoserver-1909, 3.1-nanoserver-1909 | Windows Server, version 1909 | [amd64](placeholder) | 08/20/2020
| &nbsp;&nbsp;&nbsp;&nbsp;&#8627;&nbsp;&nbsp;&nbsp;3.1.7-nanoserver-1903, 3.1-nanoserver-1903 | Windows Server, version 1903 | [amd64](placeholder) | 08/20/2020
| &nbsp;&nbsp;&nbsp;&nbsp;&#8627;&nbsp;&nbsp;&nbsp;3.1.7-nanoserver-1809, 3.1-nanoserver-1809 | Windows Server 2019 | [amd64](placeholder) | 08/20/2020
| 3.1.7-alpine3.12, 3.1-alpine3.12, 3.1-alpine | Alpine 3.12 | [amd64](placeholder), [arm64v8](placeholder) | 08/20/2020
| 3.1.7-alpine3.11, 3.1-alpine3.11 | Alpine 3.11 | [amd64](placeholder), [arm64v8](placeholder) | 08/20/2020
| 3.1.7-focal, 3.1-focal | Ubuntu 20.04 | [amd64](placeholder), [arm64v8](placeholder), [arm32v7](placeholder) | 08/20/2020
| 3.1.7-bionic, 3.1-bionic | Ubuntu 18.04 | [amd64](placeholder), [arm64v8](placeholder), [arm32v7](placeholder) | 08/20/2020
| 2.1.21, 2.1, latest | Multi-platform | amd64, arm32v7 | 08/20/2020
| &nbsp;&nbsp;&nbsp;&nbsp;&#8627;&nbsp;&nbsp;&nbsp;2.1.21-buster-slim, 2.1-buster-slim | Debian 10 | [amd64](placeholder), [arm32v7](placeholder) | 08/20/2020
| &nbsp;&nbsp;&nbsp;&nbsp;&#8627;&nbsp;&nbsp;&nbsp;2.1.21-nanoserver-2004, 2.1-nanoserver-2004 | Windows Server, version 2004 | [amd64](placeholder) | 08/20/2020
| &nbsp;&nbsp;&nbsp;&nbsp;&#8627;&nbsp;&nbsp;&nbsp;2.1.21-nanoserver-1909, 2.1-nanoserver-1909 | Windows Server, version 1909 | [amd64](placeholder) | 08/20/2020
| &nbsp;&nbsp;&nbsp;&nbsp;&#8627;&nbsp;&nbsp;&nbsp;2.1.21-nanoserver-1903, 2.1-nanoserver-1903 | Windows Server, version 1903 | [amd64](placeholder) | 08/20/2020
| &nbsp;&nbsp;&nbsp;&nbsp;&#8627;&nbsp;&nbsp;&nbsp;2.1.21-nanoserver-1809, 2.1-nanoserver-1809 | Windows Server 2019 | [amd64](placeholder) | 08/20/2020
| 2.1.21-alpine3.12, 2.1-alpine3.12, 2.1-alpine | Alpine 3.12 | [amd64](placeholder) | 08/20/2020
| 2.1.21-alpine3.11, 2.1-alpine3.11 | Alpine 3.11 | [amd64](placeholder) | 08/20/2020
| 2.1.21-focal, 2.1-focal | Ubuntu 20.04 | [amd64](placeholder), [arm32v7](placeholder) | 08/20/2020
| 2.1.21-bionic, 2.1-bionic | Ubuntu 18.04 | [amd64](placeholder), [arm32v7](placeholder) | 08/20/2020

## Linux amd64 Tags

Tags | Dockerfile | OS Version | Last Modified
-----------| -------------| -------------| -------------
5.0.0-buster-slim-amd64, 5.0-buster-slim-amd64 | Debian 10 | [amd64](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/5.0/buster-slim/amd64/Dockerfile) | 08/20/2020
5.0.0-alpine3.12-amd64, 5.0-alpine3.12-amd64, 5.0-alpine-amd64 | Alpine 3.12 | [amd64](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/5.0/alpine3.12/amd64/Dockerfile) | 08/20/2020
5.0.0-focal-amd64, 5.0-focal-amd64 | Ubuntu 20.04 | [amd64](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/5.0/focal/amd64/Dockerfile) | 08/20/2020
3.1.7-buster-slim-amd64, 3.1-buster-slim-amd64 | Debian 10 | [amd64](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/3.1/buster-slim/amd64/Dockerfile) | 08/20/2020
3.1.7-alpine3.12-amd64, 3.1-alpine3.12-amd64, 3.1-alpine-amd64 | Alpine 3.12 | [amd64](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/3.1/alpine3.12/amd64/Dockerfile) | 08/20/2020
3.1.7-alpine3.11-amd64, 3.1-alpine3.11-amd64 | Alpine 3.11 | [amd64](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/3.1/alpine3.11/amd64/Dockerfile) | 08/20/2020
3.1.7-focal-amd64, 3.1-focal-amd64 | Ubuntu 20.04 | [amd64](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/3.1/focal/amd64/Dockerfile) | 08/20/2020
3.1.7-bionic-amd64, 3.1-bionic-amd64 | Ubuntu 18.04 | [amd64](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/3.1/bionic/amd64/Dockerfile) | 08/20/2020
2.1.21-stretch-slim-amd64, 2.1-stretch-slim-amd64 | Debian 9 | [amd64](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/2.1/stretch-slim/amd64/Dockerfile) | 08/20/2020
2.1.21-alpine3.12-amd64, 2.1-alpine3.12-amd64, 2.1-alpine-amd64 | Alpine 3.12 | [amd64](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/2.1/alpine3.12/amd64/Dockerfile) | 08/20/2020
2.1.21-alpine3.11-amd64, 2.1-alpine3.11-amd64 | Alpine 3.11 | [amd64](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/2.1/alpine3.11/amd64/Dockerfile) | 08/20/2020
2.1.21-focal-amd64, 2.1-focal-amd64 | Ubuntu 20.04 | [amd64](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/2.1/focal/amd64/Dockerfile) | 08/20/2020
2.1.21-bionic-amd64, 2.1-bionic-amd64 | Ubuntu 18.04 | [amd64](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/2.1/bionic/amd64/Dockerfile) | 08/20/2020

## Linux arm64 Tags

Tags | Dockerfile | OS Version | Last Modified
-----------| -------------| -------------| -------------
5.0.0-buster-slim-arm64v8, 5.0-buster-slim-arm64v8 | Debian 10 | [arm64v8](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/5.0/buster-slim/arm64v8/Dockerfile) | 08/20/2020
5.0.0-alpine3.12-arm64v8, 5.0-alpine3.12-arm64v8, 5.0-alpine-arm64v8 | Alpine 3.12 | [arm64v8](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/5.0/alpine3.12/arm64v8/Dockerfile) | 08/20/2020
5.0.0-focal-arm64v8, 5.0-focal-arm64v8 | Ubuntu 20.04 | [arm64v8](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/5.0/focal/arm64v8/Dockerfile) | 08/20/2020
3.1.7-buster-slim-arm64v8, 3.1-buster-slim-arm64v8 | Debian 10 | [arm64v8](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/3.1/buster-slim/arm64v8/Dockerfile) | 08/20/2020
3.1.7-alpine3.12-arm64v8, 3.1-alpine3.12-arm64v8, 3.1-alpine-arm64v8 | Alpine 3.12 | [arm64v8](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/3.1/alpine3.12/arm64v8/Dockerfile) | 08/20/2020
3.1.7-alpine3.11-arm64v8, 3.1-alpine3.11-arm64v8 | Alpine 3.11 | [arm64v8](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/3.1/alpine3.11/arm64v8/Dockerfile) | 08/20/2020
3.1.7-focal-arm64v8, 3.1-focal-arm64v8 | Ubuntu 20.04 | [arm64v8](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/3.1/focal/arm64v8/Dockerfile) | 08/20/2020
3.1.7-bionic-arm64v8, 3.1-bionic-arm64v8 | Ubuntu 18.04 | [arm64v8](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/3.1/bionic/arm64v8/Dockerfile) | 08/20/2020

## Linux arm32 Tags

Tags | Dockerfile | OS Version | Last Modified
-----------| -------------| -------------| -------------
5.0.0-buster-slim-arm32v7, 5.0-buster-slim-arm32v7 | Debian 10 | [arm32v7](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/5.0/buster-slim/arm32v7/Dockerfile) | 08/20/2020
5.0.0-focal-arm32v7, 5.0-focal-arm32v7 | Ubuntu 20.04 | [arm32v7](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/5.0/focal/arm32v7/Dockerfile) | 08/20/2020
3.1.7-buster-slim-arm32v7, 3.1-buster-slim-arm32v7 | Debian 10 | [arm32v7](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/3.1/buster-slim/arm32v7/Dockerfile) | 08/20/2020
3.1.7-focal-arm32v7, 3.1-focal-arm32v7 | Ubuntu 20.04 | [arm32v7](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/3.1/focal/arm32v7/Dockerfile) | 08/20/2020
3.1.7-bionic-arm32v7, 3.1-bionic-arm32v7 | Ubuntu 18.04 | [arm32v7](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/3.1/bionic/arm32v7/Dockerfile) | 08/20/2020
2.1.21-stretch-slim-arm32v7, 2.1-stretch-slim-arm32v7 | Debian 9 | [arm32v7](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/2.1/stretch-slim/arm32v7/Dockerfile) | 08/20/2020
2.1.21-focal-arm32v7, 2.1-focal-arm32v7 | Ubuntu 20.04 | [arm32v7](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/2.1/focal/arm32v7/Dockerfile) | 08/20/2020
2.1.21-bionic-arm32v7, 2.1-bionic-arm32v7 | Ubuntu 18.04 | [arm32v7](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/2.1/bionic/arm32v7/Dockerfile) | 08/20/2020

## Windows amd64 Tags

| Tags | OS Version | Arch / Dockerfile | Last Modified
-----------| -----------| -------------| -------------
| 5.0.0-nanoserver-2004-amd64, 5.0-nanoserver-2004-amd64 | Windows Server, version 2004 | [amd64](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/5.0/nanoserver-2004/amd64/Dockerfile) | 08/20/2020
| 5.0.0-nanoserver-1909-amd64, 5.0-nanoserver-1909-amd64 | Windows Server, version 1909 | [amd64](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/5.0/nanoserver-1909/amd64/Dockerfile) | 08/20/2020
| 5.0.0-nanoserver-1903-amd64, 5.0-nanoserver-1903-amd64 | Windows Server, version 1903 | [amd64](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/5.0/nanoserver-1903/amd64/Dockerfile) | 08/20/2020
| 5.0.0-nanoserver-1809-amd64, 5.0-nanoserver-1809-amd64 | Windows Server 2019 | [amd64](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/5.0/nanoserver-1809/amd64/Dockerfile) | 08/20/2020
| 3.1.7-nanoserver-2004-amd64, 3.1-nanoserver-2004-amd64 | Windows Server, version 2004 | [amd64](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/3.1/nanoserver-2004/amd64/Dockerfile) | 08/20/2020
| 3.1.7-nanoserver-1909-amd64, 3.1-nanoserver-1909-amd64 | Windows Server, version 1909 | [amd64](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/3.1/nanoserver-1909/amd64/Dockerfile) | 08/20/2020
| 3.1.7-nanoserver-1903-amd64, 3.1-nanoserver-1903-amd64 | Windows Server, version 1903 | [amd64](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/3.1/nanoserver-1903/amd64/Dockerfile) | 08/20/2020
| 3.1.7-nanoserver-1809-amd64, 3.1-nanoserver-1809-amd64 | Windows Server 2019 | [amd64](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/3.1/nanoserver-1809/amd64/Dockerfile) | 08/20/2020
| 2.1.21-nanoserver-2004-amd64, 2.1-nanoserver-2004-amd64 | Windows Server, version 2004 | [amd64](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/2.1/nanoserver-2004/amd64/Dockerfile) | 08/20/2020
| 2.1.21-nanoserver-1909-amd64, 2.1-nanoserver-1909-amd64 | Windows Server, version 1909 | [amd64](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/2.1/nanoserver-1909/amd64/Dockerfile) | 08/20/2020
| 2.1.21-nanoserver-1903-amd64, 2.1-nanoserver-1903-amd64 | Windows Server, version 1903 | [amd64](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/2.1/nanoserver-1903/amd64/Dockerfile) | 08/20/2020
| 2.1.21-nanoserver-1809-amd64, 2.1-nanoserver-1809-amd64 | Windows Server 2019 | [amd64](https://github.com/dotnet/dotnet-docker/blob/master/src/runtime/2.1/nanoserver-1809/amd64/Dockerfile) | 08/20/2020

You can retrieve a list of all available tags for winamd64/dotnet/runtime at https://mcr.microsoft.com/v2/winamd64/dotnet/runtime/tags/list.

# Support

See [Microsoft Support for .NET Core](https://github.com/dotnet/core/blob/master/microsoft-support.md) for the support lifecycle.

# Image Update Policy

* We update the supported .NET Core images within 12 hours of any updates to their base images (e.g. debian:buster-slim, windows/nanoserver:1909, buildpack-deps:bionic-scm, etc.).
* We publish .NET Core images as part of releasing new versions of .NET Core including major/minor and servicing.

# Feedback

* [File a .NET Core Docker issue](https://github.com/dotnet/dotnet-docker/issues)
* [File a .NET Core issue](https://github.com/dotnet/core/issues)
* [File an ASP.NET Core issue](https://github.com/aspnet/home/issues)
* [File an issue for other .NET components](https://github.com/dotnet/core/blob/master/Documentation/core-repos.md)
* [File a Visual Studio Docker Tools issue](https://github.com/microsoft/dockertools/issues)
* [File a Microsoft Container Registry (MCR) issue](https://github.com/microsoft/containerregistry/issues)
* [Ask on Stack Overflow](https://stackoverflow.com/questions/tagged/.net-core)
* [Contact Microsoft Support](https://support.microsoft.com/contactus/)

# License

* Legal Notice: [Container License Information](https://aka.ms/mcr/osslegalnotice)
* [.NET Core license](https://github.com/dotnet/dotnet-docker/blob/master/LICENSE)
* [Discover licensing for Linux image contents](https://github.com/dotnet/dotnet-docker/blob/master/documentation/image-artifact-details.md)
* [Windows Nano Server license](https://hub.docker.com/_/microsoft-windows-nanoserver/) (only applies to Windows containers)
* [Pricing and licensing for Windows Server 2019](https://www.microsoft.com/cloud-platform/windows-server-pricing)