# uptold-pos-releases

The public update feed for the **Uptold POS** desktop app (Windows and Mac).

This repo holds GitHub Releases only: the installers plus `latest.yml`, `latest-mac.yml` and `beta.yml`, which the app's auto-updater (electron-updater) reads. There is no code here; the app is built from `packages/pos-hub` in the monorepo by `pos-hub-release.yml`.

How to publish a release, staged rollouts, betas and pinning: `packages/pos-hub/RELEASE.md` in the monorepo.
