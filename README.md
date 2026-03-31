# Banking Application - Release Orchestration

CloudBees Unify Application workflows for managing releases of the banking app across environments.

## Structure

- `.cloudbees/workflows/deployer.yaml` - Reusable workflow that orchestrates component deployments
- `.cloudbees/workflows/staged.yaml` - Staged workflow for release management across dev/staging/prod

## Environments

- **dev** - Development environment
- **staging** - Staging environment
- **prod** - Production environment

## Related Repositories

- Component: [banking-app](https://github.com/tdesai2705/banking-app)
