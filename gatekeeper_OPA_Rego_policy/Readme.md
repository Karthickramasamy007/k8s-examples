# Install Gatekeeper on K8s
    - kubectl apply -f https://raw.githubusercontent.com/open-policy-agent/gatekeeper/v3.18.2/deploy/gatekeeper.yaml

    - You can push to gitrepo and use argocd for policy implementation.
    - You have to have gatekeeper installed first
    - You can use the sample cluster role and binding, so only allowed user/service account can create or modidy policies using gatekeeper. 