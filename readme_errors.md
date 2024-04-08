# Errors
1. Installation gets stuck, specially at Db steps
> I increased CPU and Ram to 4cpu & 16gb. Kept on re-running the installation playbook

2. Ran out of disk error
> Increase disk from VMware fusion setting. Then increase disk from VM's disk utility

3. Cockpit containers
> They do not show correct status of podman containers. Use `podman ps` instead