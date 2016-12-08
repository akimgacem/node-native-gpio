# nodejs Native Module

- tizen 3.0
- artik 10
- [nodejs 4.4.3](https://git.tizen.org/cgit/platform/upstream/nodejs)

## Development Environment

### Ubuntu 16.04 LTS

### GBS(Git Build System)

refer to [how to install gbs](https://source.tizen.org/ko/documentation/developer-guide/getting-started-guide/installing-development-tools?langredirect=1)

## Setup

```
$ git clone git://git.tizen.org/platform/upstream/nodejs nodejs-tizen
$ cd nodejs-tizen && git checkout b9b28b06449b0d6bac92ebc6c232839321e3d469
```

## Build

### build

```
$ gbs build -P "tizen_common_3.0b_artik_armv7l" --arch armv7l --include-all
```

## Test

### Install

```
$ rpm -ivh nodejs-4.4.3-1.armv7l.rpm
```
