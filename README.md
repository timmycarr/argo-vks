# argo-vks
Demo Repo for Ephemeral Cluster Workflows

Configure argo to work between repo and appropriate Supervisor NS:
argocd app create vks --repo https://github.com/timmycarr/argo-vks --path cluster-lcm --dest-namespace kubecon-3ywqg --dest-server https://172.25.0.11:443
