Objectif cette année :
- Archi dans un premier temps en docker compose, portainer
- Structure LAMP : HaProxy (ou Traefik) + Nginx + PHP + MySQL (en réplication maitre esclave ou regarder MariaDB Galera Cluster)
- Réseau de log (ELK / Fluentd / Metricbeat / Zookeeper / OU Prom Loki Grafana ? / Syslog, rsyslog, syslog-ng ? Graylog
- Supervision netdata ? ou Prometheus + Node Exporter
- Système d'authen interne + système 2FA, par mail, téléphone ? OTP / Email / SMS, Keycloak + OpenID Connect / SAML, SSO ? (FreeIPA ou Keyclock)
- RBAC ?
- Automatiser tout le processus d'installation / de down (script)
- Protocole de connexion à distance : SSH, RDP, VNC ? Kerberos ?
- Système de surveillance par vidéo ? ZoneMinder ou Shinobi 
- Partage de connexion par lien ?
- Redis / Memcached (cache), Vanish ????
- Hardening , avec fail2ban, SELinux, AppArmor, suricata
- Connexion distante (option SSH clés)
- Ansible pour déployer l'infra 
- vault hashicorp ?
- système de backup ? BorgBackup
- dashboard global avec vu en temps réel sur tous les services, connexion en temps réel, etc.
- assistant RH, chatbot pour demande aide (cf. chatbot redhat) (alban)
- replays des sessions possible ?
- bloc-notes, clavier, etc.
- faire du JIT / PoLP
- Harbor pour le pull des images de façon air-gapped


Suite : 
- Migrer vers une infra openshift / k8s
- Traefik ou Istio pour les ingress
- faire de l'argoCD ou jenkins
- Velero pour la backup
- LAMP devient Helm Charts
- security-as-code : falco, kyverno, pour la politique de sécu
- haute dispo : Harvester
- Déployer une partie sur proxmox avec un bridge vers ope,shift pour hybridation
- stockage distribué : Ceph/Rook, Longhorn
- Utilisation de firewall dynamique (iptables/nftables) qui ouvre les ports uniquement pendant l’accès
- si on est vraiment des goats on fait du air-gapped (déconnecté d'internet pour les env ultra sensibles)
 
