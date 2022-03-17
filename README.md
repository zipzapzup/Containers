# Containers
Container and Setting up development environment for windows.

1. As Administrator run: ./enable_hyperv.bat
2. powershell wsl --install
    1. Note: Install Windows Subsystem for Linux
3. Install Docker for Desktop
4. Restart Windows
5. Install kubectl 
    1. [Kubernetes.IO](https://kubernetes.io/docs/tasks/tools/install-kubectl-windows/#install-kubectl-binary-with-curl-on-windows)
    2. curl -LO "https://dl.k8s.io/release/v1.23.0/bin/windows/amd64/kubectl.exe"
7. To get started with kubernetes, there are usually a few different options. Each have its own advantages:
    1. Kind
    2. Minikube
    3. Kubeadm
    4. k3s
