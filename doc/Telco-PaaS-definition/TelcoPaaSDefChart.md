# XGVela Telco PaaS Definition
|#|Functions|Description|Software (project name & version)|Telco enhancement point|Tag|Priority|Committer|
|---|---|---|---|---|---|---|---|
|1|Container|(1) Runtime: support Open Container Initiative (OCI) runtime spec and Kubernetes Container Runtime Interface (CRI) to integrate with K8s for container management; (2) Resource management: memory, CPU, NUMA, HW accelerators; (3) VNF/CNF: support managing VNF and CNF in same cluster|(1) ICN: https://wiki.akraino.org/display/AK/ICN+R3++Release (2) Kubevirt: https://github.com/kubevirt/kubevirt||Infrastructure||
|2|Orchestration|(1) Orchestration application with K8s native support (2) Orchestration application with K8s Application package manager (e.g. helm) (3)  Cross-sites orchestration|(1) helm: https://github.com/helm/helm (2)EMCO: https://git.onap.org/multicloud/k8s||Infrastructure||
|3|Storage|(1) Local storage on HDD (Hard Disk Drive) and SSD (Solid State Drive) (2) Remote storage (e.g. iSCSI, NFS etc.) (3) Catalogue/block storage (4) replication and encryption|||Infrastructure||
|4|Network|(1) Attaching multiple network interfaces to pod (e.g. CNI meta plugin/CNI multiplexer); (2) Managing and attaching pod to multiple virtual networks; (3) Attaching pod to provider network; (4) Service Function Chain (SFC); (5) Management of CNF network; (6) Multiple tenancy; (7) IPv4 and IPv6|(1) OVN-for-K8s NFV controller: https://github.com/opnfv/ovn4nfv-k8s-plugin (2) Multus: https://github.com/intel/multus-cni||Infrastructure||
|5|Deployment & configuration|Telco PaaS should be able to run on environrment including: OpenStack, K8S, VMWare, AWS, Azure, etc.|||PaaS-Provisioning||
|6|Image||||PaaS-Provisioning||
|7|Security||||PaaS-Provisioning||
|8|Crypto & key management||||PaaS-Provisioning||
|9|Service discovery||||PaaS-Management||
|10|API gateway||||PaaS-Provisioning||
|11|DB||||PaaS-Application support||
|12|Streaming & messaging||||PaaS-Application support||
|13|Application definition & management|e.g. application packet management tool-helm|||PaaS-Application support||
|14|CI/CD||||PaaS-Application support||
|15|Service mesh||||PaaS-Application support||
|16|Load balancer||||PaaS-Application support||
|17|Firewall||||PaaS-Application support||
|18|DPI||||PaaS-Application support||
|19|NAT||||PaaS-Application support||
|20|Hardware acceleration|(1) Hardware feature detect: NFD (2) Nic: SRIOV, FPGA (3) QAT: security and data compression (3) AI workload: FPGA, VPU (4) CPU core management: CMK|(1) NFD: https://github.com/kubernetes-sigs/node-feature-discovery (2) CMK: https://github.com/intel/CPU-Manager-for-Kubernetes (3 )QAT/FPGA device plugin: https://github.com/intel/intel-device-plugins-for-kubernetes (4)SRIOV device plugin: https://github.com/intel/sriov-network-device-plugin||PaaS-Application support||
|21|Monitorying||||Observerbility & maintainance||
|22|Logging||||Observerbility & maintainance||
|23|Tracing||||Observerbility & maintainance||
|24|SSO||||Observerbility & maintainance||
|25|API to ONAP & OSS||||Observerbility & maintainance||
