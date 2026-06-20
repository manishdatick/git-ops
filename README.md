<<<<<<< HEAD
# FluxCD GitOps Repository

This repository contains a minimal FluxCD layout for bootstrapping Flux into an AKS cluster
and a sample application (demo-app). Replace placeholders (like repository URL) before bootstrapping.

Bootstrap example (replace placeholders):

```bash
# install flux CLI: https://fluxcd.io/docs/installation/
flux bootstrap git \
  --owner=<github-org-or-user> \
  --repository=<repo-name> \
  --branch=main \
  --path=./flux-system \
  --personal
```

After bootstrapping, Flux will sync the `flux-system` resources and then the `apps` directory.
=======
# git-ops
>>>>>>> origin/main
