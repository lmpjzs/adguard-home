# AdGuard Home — L7 EKS

GitOps path `k8s/` (ArgoCD). MetalLB VIP `192.168.1.216`.

- DNS: UDP/TCP 53
- UI setup (primeiro acesso): http://192.168.1.216:3000
- UI depois do wizard: http://192.168.1.216/
- DHCP do AdGuard **off** — UniFi/USG continua DHCP
- DNS da casa: apontar DHCP UniFi para `192.168.1.216` só depois de validar

Rewrite DNS = hostname → IP. Porta/path não entram no DNS.
