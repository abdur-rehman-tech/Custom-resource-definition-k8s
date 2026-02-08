# Kubernetes Custom Resource Definition (CRD)

[![Kubernetes Version](https://img.shields.io/badge/Kubernetes-1.24+-green.svg?style=flat-square)](https://kubernetes.io/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)

This project demonstrates creating and managing **Custom Resource Definitions (CRDs)** in Kubernetes.

---

## 🚀 Features

- Define your **own Kubernetes resources**.
- Integrate seamlessly with Kubernetes API.
- Extend Kubernetes for **custom controllers or operators**.
- Ideal for **cloud-native applications**.

---

## 🛠 Prerequisites

- Kubernetes cluster (local, cloud, or KIND)
- `kubectl` installed and configured

---

## ⚡ Installation

Apply the CRD:

```bash
kubectl apply -f crd.yaml
