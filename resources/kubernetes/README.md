# Introduction
These are from a lead system engineer at VNG, [thanhtn208](https://github.com/thanhtn208)

# Slide
https://github.com/thanhtn208/Introduction-to-Kubernetes

# Cài đặt K8S dùng kubeadm trên ubuntu 22.04

https://computingforgeeks.com/install-kubernetes-cluster-ubuntu-jammy/

# Sử dụng docker làm container runtime
https://computingforgeeks.com/install-kubernetes-cluster-ubuntu-jammy

# So sánh 3 giải pháp monitor hệ thống và ứng dụng trên K8S (thường dùng)

https://prohoster.info/en/blog/administrirovanie/vybiraem-hranilishhe-dannyh-dlya-prometheus-thanos-vs-victoriametrics

- Thanos: https://github.com/thanos-io/thanos#architecture-overview
- Victoria Metrics:
    https://github.com/VictoriaMetrics/VictoriaMetrics
    https://docs.victoriametrics.com/guides/k8s-monitoring-via-vm-single.html

# Concept về Flannel CNI (networking trong K8S)

https://banzaicloud.com/docs/pipeline/security/network-policy/network-plugins/
https://mvallim.github.io/kubernetes-under-the-hood/documentation/kube-flannel.html
https://msazure.club/flannel-networking-demystify

# Migrate từ Flannel --> Calico (hỗ trợ network policy)

https://docs.tigera.io/calico/latest/getting-started/kubernetes/flannel/migration-from-flannel

# Các khái niệm networking trong linux (sử dụng trong K8S cni)

https://developers.redhat.com/blog/2018/10/22/introduction-to-linux-interfaces-for-virtual-networking#veth

# Giới thiệu MetalLB (Load Balancer cho bare-mental):

https://kb.vidinet.net/central/latest/load-balancing-and-metallb-c-arc

+ Cài đặt:
https://computingforgeeks.com/deploy-metallb-load-balancer-on-kubernetes/  
https://github.com/lacoski/kubernetes-note/blob/main/docs/setup/install-metallb.md

# Ingress controller:

https://www.bmc.com/blogs/kubernetes-ingress/
https://www.kubecost.com/kubernetes-devops-tools/traefik-vs-nginx/
https://kubevious.io/blog/post/comparing-top-ingress-controllers-for-kubernetes

- Cài đặt (nginx với metallb cấp external ip cho ingress svc)

https://nvtienanh.info/blog/cai-dat-metallb-va-ingress-nginx-tren-bare-metal-kubernetes-cluster


CNI:
- https://github.com/cilium/cilium
- https://docs.tigera.io/calico/latest/networking/configuring/mtu

Egress GW:
- https://cilium.io/use-cases/egress-gateway/

# Storage cho K8S
https://www.slideshare.net/SeanCohen/storage-101-rook-and-ceph-open-infrastructure-denver-2019
https://www.velotio.com/engineering-blog/kubernetes-csi-in-action-explained-with-features-and-use-cases
