# `[robin@fedora-kde ~]$ ./whoami`

> **Apprenti SysAdmin & Dompteur de Serveurs**
> *Tourne à l'eau plate, Fedora & l'acharnement pur.*

Salut, c'est **Robin** (*aka Galaxix*). Mon délire ? Prendre de la ferraille bare-metal et la transformer en infrastructure qui tient la charge. De mon chauffage d'appoint (un Fujitsu dans ma chambre) jusqu'aux dédiés en Pologne, j'aime quand ça ping et quand le routage est propre.

Je ne suis **absolument pas un dev**. Si tu cherches des dépôts pleins de code React ou de CSS magnifique, tu t'es trompé d'adresse (d'où mon GitHub vide, je planque jalousement mes scripts bash faits à l'arrache). Moi, mon truc, c'est le YAML, les hyperviseurs et m'assurer que la prod des autres ne crashe pas.

---

### ⚙️ `./stack_trace` - L'Arsenal

**[ SYS.VIRT ] - Systèmes & Virtualisation**
* **Hyperviseurs :** Proxmox VE & Proxmox Backup Server (parce qu'un `rm -rf /` est vite arrivé)
* **OS :** Fedora KDE (Daily), Debian / Ubuntu Server
* **Conteneurs :** Docker couplé à Coolify (le Vercel du pauvre, mais en mieux et self-hosted)
* **Next step :** Bouffer du Nova et Neutron sur OpenStack.

**[ NET.SEC ] - Réseau & Sécurité**
* **Core :** Tunnels Cloudflare, Routage Multi-IP & Failover (pour séparer le Web du Game)
* **DNS & Monit :** AdGuard Home, Uptime Kuma, Netdata

**[ HARDWARE ] - La Ferraille (Base of Ops: Rouen, FR)**
* **On-Premise :** Fujitsu Primergy RX300 S7 (Xeon E5) + Mini HP
* **Stockage :** RAID 5 (*On vit dangereusement, la reconstruction d'un disque mort, c'est pour l'adrénaline*) + Switch 3Com Gigabit (une antiquité qui survivra à l'apocalypse).

---

### 🌍 `./architecture` - En Production

Je maintiens un lab hybride pour me faire la main avant la vraie prod en entreprise :

* 🔥 **[Node Cloud OVH - Warsaw] :** Xeon-D 1540, 32Go ECC NVMe. J'y gère un routage Failover maison pour isoler proprement KeyHelp (Web) et Pterodactyl (Game).
* 🏗️ **[Le Bunker Local] :** Le lab à la maison. L'endroit où je pète des configs réseau exprès *(ou pas... oups)* pour apprendre à les réparer.

---

### 🚀 `./roadmap` - Objectif 2026

- [ ] **Trouver une alternance :** Intégrer une vraie équipe tech pour mon bac+2/bac+3 en administration systèmes et réseaux. Faire du support N1/N2 pour commencer ne me fait absolument pas peur, il faut bien apprendre à réparer les conneries des utilisateurs avant d'architecturer le réseau.
- [ ] **Mastering IaaS :** Déployer du cloud privé avec OpenStack sans faire fondre le compteur Linky.

---

### 📡 `./ping`

Tu veux discuter infra, peering, ou m'expliquer pourquoi mon switch 3Com a sa place dans un musée ? 

📫 **Drop un paquet UDP :** [me@robin-predent.com](mailto:me@robin-predent.com)
