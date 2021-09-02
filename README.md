# FakeNRF Environment

this environment will always be read by fluxcd in the kubernetes

in this case, once pull request is merged, changing release for nnrf-nfm from v0.1 to v0.2 or changing release for nnrf-disc from v0.1 to v0.2 inside the yaml, flux will then reconciliate with the new commit and apply the new yaml file automatically.

