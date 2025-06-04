# 🧪 HomeLab personnel

Mon environnement de test pour tout ce qui touche à la **virtualisation**, l’**infra**, la **sécurité réseau** et la **cybersécurité**.  
Tout tourne sur une VM dédiée, avec snapshots réguliers.

---

## 🧱 Infra actuelle
- 🖥️ VMware Workstation / ESXi (selon besoins)
- 🧰 VMs :
  - Kali Linux (pentest)
  - Windows Server (AD / GPO / RDS)
  - pfSense (pare-feu)
  - Debian (QUANTUM, services IA)

---

## 📁 Contenu du dépôt
- `topology.svg` – Schéma visuel de l'infra
- `vm-setup/` – Scripts d’installation / snapshots
- `network-tests/` – Scénarios testés (MITM, segmentation)
- `notes.md` – Retour d’expérience & évolutions

---

## 🛡️ Objectifs du lab
- Tester des attaques/défenses en environnement isolé
- Simuler une infra complète type PME
- Former à l’analyse post-incident
