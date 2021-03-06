# Supported Platforms #

Ignition is currently only supported for the following platforms:

- [Bare Metal](https://coreos.com/os/docs/latest/installing-to-disk.html) - Use
  the `coreos.config.url` kernel parameter to provide a URL to the
  configuration. The URL can use the `http://` scheme to specify a remote
  config or the `oem://` scheme to specify a local config, rooted in
  `/usr/share/oem`.
- [PXE](https://coreos.com/os/docs/latest/booting-with-pxe.html) - Use the
  `coreos.config.url` kernel parameter to provide a URL to the configuration.
  The URL can use the `http://` scheme to specify a remote config or the
  `oem://` scheme to specify a local config, rooted in `/usr/share/oem`.
- [Amazon EC2](https://coreos.com/os/docs/latest/booting-on-ec2.html) -
  Ignition will read its configuration from the userdata and append the SSH
  keys listed in the instance metadata.

Ignition is under active development so expect this list to expand in the
coming months.
