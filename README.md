# All in Bash
<img width="220" alt="All_in_Bash" src="https://github.com/rafaelurrutiasilva/images/blob/main/logos/bash_logo.png" align=left> <br>
In this repo you will find a bunch of scripts written in Bash.<br>
They are categorized for various purposes, such as modern apps, observability, monitoring, and more.<br><br>
All scripts are present in my other repositories but are gathered here for easier access and organization.<br>

---
## A Mix of Originality and Community Inspiration
It is not my intention to steal or take credit for others' work. My scripts are a product of both my own creation and a lot of borrowing and inspiration from like-minded individuals out there on forums, manuals, and the internet.

---
## Modern Apps and Observability
Script | Function
-------|---------
[generate_manifests.sh](https://github.com/rafaelurrutiasilva/Generate_K8s_Manifests_Using_Helm/blob/main/generate_manifests.sh) | Used to generate Kubernetes manifests using Helm and Kubeseal.
[install_prometheus_server.sh](https://github.com/rafaelurrutiasilva/Prometheus_on_PhotonOS/blob/main/scripts/install_prometheus_server.sh) | Install and confugure all you need to run a Prometheus server.
[install_prometheus_exporter.sh](https://github.com/rafaelurrutiasilva/Prometheus_on_PhotonOS/blob/main/scripts/install_prometheus_exporter.sh) | Install and confugure all you need to run a Prometheus node-exporter.

## Monitoring and Nagios Check
They are all tested in CentOS, Suse, RHEL and Photon OS
Script | Function
-------|---------
[check_by_top](https://github.com/rafaelurrutiasilva/nagios-bash-plugins/blob/main/plugins/check_by_top) | Will check tasks, cpu, mem or swap using command top.
[check_disk](https://github.com/rafaelurrutiasilva/nagios-bash-plugins/blob/main/plugins/check_disk) | Will check disk utilization.
[check_file_age](https://github.com/rafaelurrutiasilva/nagios-bash-plugins/blob/main/plugins/check_file_age) | Will check file age in min filter by name and numbers of files.
[check_ps](https://github.com/rafaelurrutiasilva/nagios-bash-plugins/blob/main/plugins/check_ps) | Will check linux process.


## Education and Home-labb
Script | Function
-------|---------
[installing_all_from_scratch.sh](https://github.com/rafaelurrutiasilva/kubeAcademy-vappliance/blob/main/scripts/installing_all_from_scratch.sh) | Used to install: helm, kind, kubectl, kubeseal, kustomize and skaffold. All in one!
