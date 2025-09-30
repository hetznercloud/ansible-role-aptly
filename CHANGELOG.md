# For next release
  * **haelekuin**
    * install: add support for upstream debian/ubuntu repositories.

*Not released yet*

# Patch Release v1.0.3 (2025-03-07)
  * **Tan Siewert**
    * repository: add missing publish_prefix option

*Released by Tan Siewert <tan.siewert@hetzner.com>*

# Patch Release v1.0.2 (2025-01-13)
  * **jonas.keidel**
    * mirror: use curl instead of ansible.builtin.url
      
      Some keys are only available as binary and the echo lookup pipe does not
      work properly. Use curl instead.

*Released by Tan Siewert <tan.siewert@hetzner.com>*

# Patch Release v1.0.1 (2023-12-18)
  * **Tom Siewert**
    * tasks: add missing tag for repository tasks

*Released by Tom Siewert <tom.siewert@hetzner.com>*

# Major Release v1.0.0 (2023-07-13)
  * **Tom Siewert**
    * Import project from internal for OSS

*Released by Tom Siewert <tom.siewert@hetzner.com>*
