Anbox Cloud is built using multiple open source software components. This guide lists those components and where to find their license information.

| Software components | Where to find their licenses |
|--|--|
| LXD images | Within the LXD image, `/usr/share/licenses` and `/usr/share/doc/*/copyright`. |
| Android | In the Android container, <br/> **Settings** > **About emulated device** > **Legal information** |
| Snaps | `/snap/<SNAP_NAME>/current/` </br>Replace <SNAP_NAME> with the name of the Snap.|
| Charms | In the container where the charm is deployed,<br/>`/$path-to-charm/COPYRIGHT` <br/> Replace $path-to-charm with the path where the charm is deployed. Usually the charm is deployed in `/var/lib/juju/agents/unit-*/charm`. |