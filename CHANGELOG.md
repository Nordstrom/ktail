# [v0.6.0](https://github.com/atombender/ktail/releases/tag/v0.6.0) (2017-12-14)

## Fixes

* Fix race conditions causing some log entries to be dropped on startup, as well as if a container is flapping.
* More fine-grained container status (e.g. a crashed container will not be tracked until it starts again).

# [v0.5.0](https://github.com/atombender/ktail/releases/tag/v0.5.0) (2017-06-01)

## Fixes

* Fix concurrent mutation bug, causing wrong pod/container to be followed.

# [v0.4.0](https://github.com/atombender/ktail/releases/tag/v0.4.0) (2017-06-01)

## Fixes

* Fix a weird edge case where logs would sometimes not appear.

# [v0.3.0](https://github.com/atombender/ktail/releases/tag/v0.3.0) (2017-05-16)

## Fixes

* Upgrade to newer Kubernetes client library, which fixes issues with the `gcp` auth provider.

# [v0.2.0](https://github.com/atombender/ktail/releases/tag/v0.2.0) (2017-05-16)

## Features

* Filtering by pod/container name.

# [v0.1.0](https://github.com/atombender/ktail/releases/tag/v0.1.0) (2017-04-24)

## Features

Initial release.
