# wsl-w0-lab

Evidence-only laboratory for Quorb issue #90 (`quorb-wsl-v1`, W0 «Observe»).

Runs a `workflow_dispatch` workflow on `windows-latest` and collects real `wsl.exe`
behavior on a hosted Windows machine: diagnostics, zero-distro state, importing
two disposable Alpine rootfs distros (one with a spaced/unicode name), default
user/home resolution via `wsl.conf`, Running/Stopped transitions, exit codes,
waking behavior of listings, and timeout/hang semantics.

Raw output is uploaded as artifact `w0-evidence`. Nothing here contains Quorb
code, credentials or Quorb configuration; this is W0 observation material only.
No work is assigned and no Quorb implementation starts from this evidence.
