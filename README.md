# Lambdulus Staging

[![Staging deploy](https://github.com/lambdulus/staging/actions/workflows/deploy.yml/badge.svg)](https://github.com/lambdulus/staging/actions/workflows/deploy.yml)

Staging site for [Lambdulus](https://github.com/lambdulus/frontend), the web
notebook for playing with lambda calculus (teaching at FIT CTU).

- Live at https://lambdulus.github.io/staging/
- Auto-deployed from the `develop` branch of `lambdulus/frontend`.
- Per-PR previews live under `pr/<branch>` (purged when the PR closes).

This repo is written by automation (`deploy.yml` rebuilds everything except
`pr/` on every deploy). Do not edit the built files by hand.
