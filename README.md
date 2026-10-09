# Alexandre Régnier

**Du japonais à l'infrastructure : j'apprends comment les systèmes tiennent debout, comment ils tombent, et comment on les sécurise.**

Étudiant en première année de BUT Informatique.
J’aime comprendre comment les choses fonctionnent, surtout quand elles cassent. Alors je construis, je casse, je répare et j’écris tout ce que j’apprends en chemin !

[LinkedIn](https://www.linkedin.com/in/alexandre-regnier2/)

---

## Ce qui m'intéresse

- **Sécurité** : approche shift-left, sécurité runtime, supply chain
- **Infrastructure** : Linux, réseau, automatisation (Ansible, Terraform)
- **Cloud-native** : Kubernetes, GitOps, observabilité

Je suis arrivé ici par un chemin atypique : une licence de japonais (LLCER, JLPT N2), puis une réorientation vers l'informatique. Apprendre une langue et apprendre l'infra, c'est le même exercice : accepter de ne rien comprendre au début, puis avancer par petites victoires.

---

## Mon terrain d'entraînement : Himmel

Un cluster **Kubernetes bare-metal** (3 Lenovo M720q) que je traite comme un environnement de production : tout est déployé en code, surveillé et scanné.

**Stack :** Terraform · Ansible · ArgoCD · Cilium (eBPF) · Prometheus / Grafana / Loki · Falco · Kyverno · Trivy · Gitleaks · Semgrep

**Un choix que j'assume :** j'ai choisi Cilium parce qu'il réunit réseau, Network Policies, observabilité (Hubble) et beaucoup d'autres fonctionnalités (L2 announcements, Gateway API…). C'est aussi une technologie qui monte, et j'avais envie de me former sur celle-ci.

Les décisions, les erreurs et les corrections sont dans **20+ devlogs** : [lire les devlogs](https://github.com/Alexandre1609-bit/Projet-Himmel/tree/main/docs).

**En ce moment :** j'approfondis ce qui est déjà déployé. La suite (Network Policies, SBOM, Cosign, Workload Identity) viendra quand je serai plus à l'aise avec l'existant.

---

## Certifications

**Obtenues :**
- **CCNA 200-301** (2026)
- LPI Linux Essentials (2025)
- TryHackMe Pre-Security & Cyber Security 101 (2025)

**Visées :** CKA et Terraform Associate, puis une certification cloud (Aws et / ou Gcp).

---

## En dehors du terminal

Piano, lecture, Japon, et probablement trop de café.

---

*Si un devlog t'a servi, ou si tu vois une erreur dans mes choix, ouvre une issue : je préfère qu'on me corrige !*
