# agrocd-template

What Is Argo CD?

- Argo CD is a declarative, GitOps continuous delivery tool for Kubernetes.
- Argo CD follows the GitOps pattern of using Git repositories as the source of truth for defining desired application states. Kubernetes manifests can be specified in several ways: like customize applications, Helm charts, Plain directory of YAML/json manifests, jsonnet files etc..
- Argo CD then automates the deployment of the desired application states in the specified target environments. Application deployments can track updates to branches, tags, or pinned to a specific version of manifests at a Git commit.


Features:

- Automated deployment of applications to specified target environments
- Support for multiple config management/templating tools (Kustomize, Helm, Jsonnet, plain-YAML)
- Ability to manage and deploy to multiple clusters
- SSO Integration (OIDC, OAuth2, LDAP, SAML 2.0, GitHub, GitLab, Microsoft, LinkedIn)
- Multi-tenancy and RBAC policies for authorization
- Rollback/Roll-anywhere to any application configuration committed in Git repository
- Health status analysis of application resources
- Automated configuration drift detection and visualization
- Automated or manual syncing of applications to its desired state
- Web UI which provides real-time view of application activity
- CLI for automation and CI integration
- Webhook integration (GitHub, BitBucket, GitLab)
