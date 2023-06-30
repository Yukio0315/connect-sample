# connect-sample

## Overview
This project is to create comfortable gRPC development environment.
This is a sample project based on [Connect-go tutorial](https://connect.build/docs/go/getting-started), [Dev Container](https://code.visualstudio.com/docs/devcontainers/containers), [protoc-gen-validate](https://github.com/bufbuild/protoc-gen-validate), [Air](https://github.com/cosmtrek/air) and so on.

## Requirement

- M1 MacBook Pro (Ventura 13.4.1)
- Docker Desktop for Mac Version 4.20.1
- VSCode Version 1.79.2
- Dev Containers v0.295.0

## Usage

```shell
git clone https://github.com/Yukio0315/connect-sample

devcontainer open # if devcontainer CLI installed

root ➜ /workspaces/connect-sample (main) $ go run ./cmd/client/main.go
YYYY/MM/DD hh:mm:ss unknown: invalid GreetRequest.Name: value length must be between 5 and 10 runes, inclusive
```
