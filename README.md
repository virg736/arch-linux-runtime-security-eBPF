## Arch Linux Runtime Security - eBPF Monitoring Lab

Kernel-level syscall monitoring using eBPF and bpftrace

## Sommaire

- [Avancement global du portfolio](#avancement-global-du-portfolio)
- [Linux Runtime Security – Lab eBPF](#linux-runtime-security--lab-ebpf)
  - [Présentation](#présentation)
  - [Objectifs](#objectifs)
  - [Perspective Attaquant – Comment un système peut être infiltré](#perspective-attaquant--comment-un-système-peut-être-infiltré)
  - [Architecture](#architecture)
  - [Implémentation](#implémentation)
    - [Étape 1 — Monitoring des exécutions (execve)](#étape-1--monitoring-des-exécutions-execve)
    - [Étape 2 — Filtrage ciblé](#étape-2--filtrage-ciblé)
    - [Étape 3 — Monitoring des accès fichiers (openat)](#étape-3--monitoring-des-accès-fichiers-openat)
  - [Concepts abordés](#concepts-abordés)
  - [Pourquoi c’est important ?](#pourquoi-cest-important)
  - [Limites observées](#limites-observées)
  - [Conclusion](#conclusion)
  - [Auteur](#auteur)

---

## Avancement global du portfolio

| Projet | Fonction | Statut |
|--------|----------|--------|
| 1 | Linux Runtime Monitoring (eBPF) | 🟢 Terminé |
| 2 | Business Logic & Human Factor Lab | ⚪ À venir |
| 3 | Tool Limitations & False Positives | ⚪ À venir |
| 4 | IA comme adversaire | ⚪ À venir |

---
