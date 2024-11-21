## Taskfiles
This repo contains a collection of taskfiles that can be used with [Taskfile](https://taskfile.dev) to automate various tasks. It is intended to be used as a reference for creating repo-based taskfiles, not as a standalone taskfile.

### Usage
To use these taskfiles, include them in your repo's taskfile like below:

```yaml
includes:
  kubernetes: https://raw.githubusercontent.com/linktivity/Taskfiles/refs/heads/master/kubernetes/Taskfile.yml
  cloudrun: https://raw.githubusercontent.com/linktivity/Taskfiles/refs/heads/master/cloudrun/Taskfile.yml
  docker: https://raw.githubusercontent.com/linktivity/Taskfiles/refs/heads/master/docker/Taskfile.yml
  ...
```