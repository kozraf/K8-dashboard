# Kubernetes Dashboard Installation Script

This repository contains a script for automating the installation of the Kubernetes Dashboard. The script checks the environment, creates necessary configurations, and deploys the dashboard service.

## Requirements

- Kubernetes cluster
- kubectl
- Internet access
- Bash shell

### Please note that this script is also used in https://github.com/kozraf/RafK8clstr - check it out for seamless K8 3-node cluster deployment!

## Installation

1. Clone the repository.
2. Make the script executable:

chmod +x k8-dashboard_install.sh

3. Run the script:

./k8-dashboard_install.sh


## Functionality

- Verifies 'metrics-server'
- Creates namespace
- Sets up a directory
- Deploys the dashboard
- Adjusts service settings
- Displays a loading animation

## Access

Use the node's IP and the designated port to access the dashboard, typically through `http://<node-ip>:32321/`.

## Security

The NodePort could expose the dashboard; use network policies or firewall rules for protection.

## Contributing

Fork the repository and submit pull requests. For major changes, open an issue for discussion.

## License

The scripts, configurations, and documentation in this project are licensed under the MIT License. This license applies only to the scripts, configurations, and documentation contained in this repository and not to the software they interact with. 
