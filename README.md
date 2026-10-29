# 🧱 Kubernetes Custom Resource Definition (CRD)

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

Extends the Kubernetes API with a custom resource: **`DevOpsBatch`** (`devopsbatches.trainwithrehman.com`).

## 📁 Files

| File | Purpose |
|---|---|
| `devops-crd.yml` | Defines the `DevOpsBatch` CRD (group `trainwithrehman.com`, version `v1`) |
| `devops-crrr.yml` | A custom resource instance of `DevOpsBatch` |

## 🚀 Usage

```bash
kubectl apply -f devops-crd.yml
kubectl get crd devopsbatches.trainwithrehman.com

kubectl apply -f devops-crrr.yml
kubectl get devopsbatches
kubectl describe devopsbatches
```

## 💡 Why CRDs matter

CRDs are the foundation of **operators** (Argo CD, cert-manager, Prometheus Operator): you define a resource, and a controller reconciles it.

---

## 👤 Author

**Abdur Rehman** · DevSecOps Engineer · Founder of [ARTechOps](https://artechops.com)

[LinkedIn](https://www.linkedin.com/in/muhamad-abdur-rehman-81777b366/) · [GitHub](https://github.com/abdur-rehman-tech) · [artechops.com](https://artechops.com)
