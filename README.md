# TechITFactory Shop (Monorepo)

Polyglot microservices e-commerce (course project), deployed to AWS EKS via GitOps.

## Services
- services/frontend  (Node)
- services/product   (Go)
- services/cart      (Python)
- services/order     (Node)

## DevOps Model (Course)
- Trunk-based development
- CI per service (GitHub Actions)
- Images pushed to DockerHub
- CD via ArgoCD from separate GitOps repo
- Promotion: Dev namespace auto-deploy on merge; Prod via Git tag/release
