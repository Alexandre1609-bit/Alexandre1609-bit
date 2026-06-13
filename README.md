---
<div align="center">

  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=E3C9A2,F5DEB3,FFF8DC&height=220&section=header&text=Alexandre%20Régnier&fontSize=60&fontColor=3B2F2F&fontAlign=50&animation=fadeIn" alt="Header Gradient" />

  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&pause=1000&color=C19A6B&center=true&vCenter=true&width=700&lines=Cloud+•+Platform+•+Security;Building+Himmel+☁️;Kubernetes+|+eBPF+|+Platform+Security;From+Japanese+to+Cloud+Security" alt="Typing SVG" />
  </a>

  <br/>

  <p align="center">
    <a href="https://github.com/Alexandre1609-bit?tab=repositories">
      <img src="https://img.shields.io/badge/Focus-Cloud%20%26%20Security-C19A6B?style=for-the-badge&logo=github&logoColor=white" alt="Focus" />
    </a>
    <a href="https://www.linkedin.com/in/alexandre-regnier2/">
      <img src="https://img.shields.io/badge/-LinkedIn-FFF8DC?style=for-the-badge&logo=linkedin&logoColor=3B2F2F&labelColor=FFF8DC" alt="LinkedIn" />
    </a>
  </p>
</div>

---

## À propos

**Étudiant en BUT Informatique (2026-2029)** | **Cloud / Platform Engineering / Cybersécurité**

Diplômé d'une licence **LLCER Japonais (JLPT N2)**, je me suis réorienté vers l’informatique avec une **passion pour les infrastructures cloud-native**.

Aujourd’hui, je consacre mon temps à **[Projet Himmel](#projet-principal--himmel)**, un **homelab Kubernetes bare-metal** conçu comme une plateforme DevSecOps production-like.

**Objectif** : Devenir **SRE / Platform Engineer / Cloud Security Engineer** dans des environnements critiques, avec un focus sur **la sécurité, l’identité et la résilience**.

---

## Projet principal : Himmel

**Homelab Kubernetes bare-metal** conçu comme une plateforme DevSecOps production-like pour apprendre, tester et implémenter les meilleures pratiques du monde professionnel.

### 🖥️ Architecture

```text
Internet → TP-Link RE605X (WiFi 6)
│
└─ TP-Link TL-SG108E (L2 Managed Switch)
   ├─ node01 (Master) - Lenovo M720q - 192.168.1.50
   ├─ node02 (Worker) - Lenovo M720q - 192.168.1.51
   └─ node03 (Worker) - Lenovo M720q - 192.168.1.52
```

**OS** : Ubuntu Server 24.04 LTS *(minimal, no Snap, official K8s binaries)*

---

### 🛠️ Stack Technique

| **Catégorie** | **Outils** | **Rôle** |
|--------------|------------|----------|
| **Orchestration** | Kubernetes v1.31 | Core platform |
| **IaC** | Terraform, Ansible | Provisioning *(Day-1)* + Configuration *(Day-2)* |
| **GitOps** | ArgoCD | Déploiement déclaratif *(App of Apps)* |
| **Réseau** | Cilium *(eBPF)* | CNI + sécurité réseau *(L7 policies)* |
| **Observabilité** | Prometheus, Grafana, Loki, Alloy, Alertmanager | Métriques, logs, alertes |
| **Sécurité** | Falco, Kyverno, Trivy, Semgrep, Gitleaks | Runtime security, policy enforcement, scans |
| **CI/CD** | GitHub Actions | Automatisation des déploiements |

---

### 📈 Résultats concrets

✅ **Cluster opérationnel** avec 3 nœuds bare-metal  
✅ **Déploiement automatisé** via Ansible + Terraform  
✅ **Observabilité complète** (métriques, logs, alertes)  
✅ **CI Security Pipeline** (Trivy, Gitleaks, Semgrep, yamllint)  
✅ **14+ devlogs** à ce jour, documentant les décisions techniques

---

### 🎯 Roadmap

| **Priorité** | **Élément** | **Statut** |
|--------------|-------------|------------|
| ⭐⭐⭐ | Cilium Network Policies | En cours |
| ⭐⭐⭐ | SBOM *(Syft/Trivy)* | À faire |
| ⭐⭐ | Cosign | À faire |
| ⭐⭐ | Workload Identity | À faire |
| ⭐ | SPIFFE/SPIRE | Long terme |
| ⭐ | Supply Chain Security | Long terme |

---

> [📖 **Lire les devlogs détaillés**](https://github.com/Alexandre1609-bit/Projet-Himmel/tree/main/docs)

---

## 📜 Certifications

### ✅ Obtenues

- **LPI Linux Essentials** *(2025)*
- **TryHackMe Pre-Security / Cyber Security 101** *(2025)*

### 🎯 En cours *(2026)*

- **CCNA 200-301** *(juillet 2026)*

### 🔮 Objectifs *(2027-2032)*

| **Domaine** | **Certification** | **Priorité** |
|------------|-------------------|--------------|
| **Kubernetes** | CKA, CKS | ⭐⭐⭐ |
| **Cloud** | AWS SAA-C03, GCP ACE | ⭐⭐⭐ |
| **IaC** | Terraform Associate | ⭐⭐⭐ |
| **Sécurité Cloud** | AWS Security Specialty, GCP PCSE | ⭐⭐ |
| **Sécurité Offensive** | OSCP | ⭐ |

> *Priorité basée sur mon projet Himmel et mon objectif SRE / Platform Engineer.*

---

## ☕ Beyond the Code

- **Pianiste** 
- **Running** 
- **Japon** 
- **Café de spécialité**
- **Apprentissage continu**
- **Documentation** 

---

N'hésitez pas à explorer les dépôts et les devlogs de Himmel ! 

Au plaisir :) 
