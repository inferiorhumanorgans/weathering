## Limitations of existing CI software

* Not even close

  * AppVeyor, Buddy, Circle — Hosted solutions are a non-starter

  * TeamCity, Bamboo — Non-free

  * Abstruse, Strider, Drone, Concourse — require docker and are thus Linux-only

  * Continuum — Java-centric

  * CruiseControl — EOL'd

  * Travis — self-hosted deployment is largely undocumented (what documentation there is hasn't been updated to match the current repo structure), GitHub only

* Maybe

  * Go — documentation is wildly out of date, UI issues have languished for 5+ years, Java agent is bloated (requires 500MB+ RAM), Golang agent is unsupported(?) and builds on Linux only using some collection of custom scripts.

  * Jenkins — documentation is lacking at best, community of cargo cultists, SSH required for remote agents.

  * Buildbot — no UI support for multiple projects/branches.  Extending the UI is extremely painful (requires Coffescript, development scripts are Linux-only)
