## Docker CE for AWS

### Getting Docker CE for AWS

"Docker CE for AWS" is free to deploy <a href="https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=Docker&templateURL=https://editions-us-east-1.s3.amazonaws.com/aws/stable/Docker.tmpl" data-rel="Stable-1" target="blank" id="aws-deploy">![Docker CE for AWS](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)</a>

### Documentation

If you don't understand something about Docker CE for AWS, the [extensive
documentation](https://docs.docker.com/docker-for-aws/) is a great place
to look for answers.

### Support

Users from the Docker CE community trade tips and tricks and discuss Docker CE
for AWS in [the user forum](https://forums.docker.com/c/docker-for-aws).

Problems with the Docker CE for AWS deployment can be filed as issues in this
([docker/for-aws](https://github.com/docker/for-aws)) repository.

### This Repository

This repository contains an issue tracker for Docker CE for AWS -- an
integrated Docker CE experience on AWS. If you find a problem
with the software, first [browse the existing
issues](https://github.com/docker/for-aws/issues) or search from the bar
at the top (`s` to focus) and then, if you don't find your issue, [open
a new issue](https://github.com/docker/for-aws/issues/new).

### Labels

Initially, issues are
[unlabeled](https://github.com/docker/for-aws/issues?q=is%3Aopen+is%3Aissue+no%3Alabel). Issues
are labeled in order to make tracking them easier. The meaning of the
labels is roughly:

| Label            | Meaning                                            |
|------------------|----------------------------------------------------|
| [area/compose](https://github.com/docker/for-aws/labels/area/compose)     | related to [docker/compose](https://github.com/docker/compose) |
| [area/database](https://github.com/docker/for-aws/labels/area/database)     | related to the configuration database |
| [area/docker](https://github.com/docker/for-aws/labels/area/docker)      | related to the Docker engine ([docker/docker](https://github.com/docker/docker)) |
| [area/gui](https://github.com/docker/for-aws/labels/area/gui)         | related to the Graphical User Interface |
| [area/linux](https://github.com/docker/for-aws/labels/area/linux)       | related to the Linux component |
| [area/mounts](https://github.com/docker/for-aws/labels/area/mounts)      | related to `-v` bind mounts |
| [area/network](https://github.com/docker/for-aws/labels/area/network)     | related to container networking |
| [area/notary](https://github.com/docker/for-aws/labels/area/notary)      | related to [docker/notary](https://github.com/docker/notary) |
| [area/aws](https://github.com/docker/for-aws/labels/area/aws)         | related to AWS integration |
| [area/startup](https://github.com/docker/for-aws/labels/area/startup)     | related to application installation or initialization |
| [area/storage](https://github.com/docker/for-aws/labels/area/storage)     | related to image and container storage ([storage drivers](https://docs.docker.com/engine/userguide/storagedriver/imagesandcontainers/)) |
| [area/volumes](https://github.com/docker/for-aws/labels/area/volumes)     | related to Docker volumes ([volume drivers](https://docs.docker.com/engine/reference/commandline/volume_create/)) |
| [kind/bug](https://github.com/docker/for-aws/labels/kind/bug)         | this issue describes a defect |
| [kind/docs](https://github.com/docker/for-aws/labels/kind/docs)        | this issue describes a documentation change |
| [kind/enhancement](https://github.com/docker/for-aws/labels/kind/enhancement) | this issue describes a change to existing functionality |
| [kind/feature](https://github.com/docker/for-aws/labels/kind/feature)     | this issue describes totally new functionality |
| [kind/performance](https://github.com/docker/for-aws/labels/kind/performance) | this issue describes a performance problem or measurement |
| [status/0-triage](https://github.com/docker/for-aws/labels/status/0-triage) | The issue needs triaging |
| [status/0-wont-fix](https://github.com/docker/for-aws/labels/status/0-wont-fix) | This issue will not be fixed and therefore can be closed |
| [status/0-more-info-needed](https://github.com/docker/for-aws/labels/status/0-more-info-needed) | The issue needs more information before it can be triaged |
| [status/1-acknowledged](https://github.com/docker/for-aws/labels/status/1-acknowledged) | The issue has been triaged and is being investigated |
| [status/2-in-progress](https://github.com/docker/for-aws/labels/status/2-in-progress) | The issue has been assigned to a engineer and is waiting a fix |
| [status/3-fixed](https://github.com/docker/for-aws/labels/status/3-fixed) | The issue has been fixed in `master` |
| [status/4-fix-released-beta](https://github.com/docker/for-aws/labels/status/4-fix-released-beta) | The fix has been released! |
| [status/4-fix-released-stable](https://github.com/docker/for-aws/labels/status/4-fix-released-stable) | The fix has been released! |

### Component Projects

Docker for AWS uses many open source components. A full list of
components and licenses is available within our [docs](https://docs.docker.com/docker-for-aws/opensource/)

