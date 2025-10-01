# Changelog

## v0.2.0

This release increases the default partition sizes from 50MB for the rootfs to 256MB
and 512MB for the default app partition.

## v0.1.1

This is an important security/bug fix that addresses Erlang CVEs for the ssh
module (see Erlang release notes).

* Changes
  * Build `libnl` to avoid compile error with `vintage_net_wifi`. Note that it's
    not possible to use WiFi, but `mix nerves.new` includes it by default for everyone.

* Package updates
  * [nerves_system_br v1.31.7](https://github.com/nerves-project/nerves_system_br/releases/tag/v1.31.7). Also
    see [nerves_system_br v1.31.6](https://github.com/nerves-project/nerves_system_br/releases/tag/v1.31.6)

* Important derived package updates
  * [Erlang/OTP 27.3.4.3](https://erlang.org/download/OTP-27.3.4.3.README.md)
  * [Buildroot 2025.02.6](https://lore.kernel.org/buildroot/b051d400-debc-4269-975a-b2992eed8d61@rnout.be/T/)

## v0.1.0

Initial release
