# DevSecOps Roadmap

This repository contains a curated roadmap to learn DevSecOps — the practice of integrating security into every phase of the software development and operations lifecycle. The roadmap is organized by skill level and includes topics, practical exercises, and recommended tools.

## How to use this roadmap

- Start at the "Beginner" level if you're new to development, operations, or security. Work through topics sequentially.
- For practitioners with some background, pick topics relevant to your work and follow the hands-on exercises.
- Continuously practice by building projects, contributing to open-source, and doing threat modeling and security reviews.

## Roadmap Overview

1. Beginner
   - Fundamentals of software development and Linux
   - Basics of networking and HTTP
   - Version control with Git
   - Introduction to security concepts: CIA triad, authentication, authorization
   - Basic cryptography concepts (hashing, symmetric/asymmetric encryption)

2. Intermediate
   - Secure coding practices and code review
   - Static Application Security Testing (SAST)
   - Dependency management and Software Composition Analysis (SCA)
   - Container fundamentals (Docker) and basic container hardening
   - CI/CD fundamentals and securing pipelines
   - Infrastructure as Code (IaC) basics (Terraform, CloudFormation)
   - Secrets management (Vault, cloud-native secrets)

3. Advanced
   - Runtime Application Self-Protection (RASP) and monitoring
   - Container orchestration security (Kubernetes hardening, network policies)
   - Cloud security best practices (IAM, VPC design, least privilege)
   - Incident response and forensics for cloud-native apps
   - Threat modeling and secure design reviews
   - Chaos engineering for resilience and security testing

## Recommended Tools & Categories

- Source code scanning (SAST): SonarQube, Semgrep
- Dependency scanning (SCA): Dependabot, Snyk, OWASP Dependency-Check
- Secret scanning and management: HashiCorp Vault, Mozilla SOPS, cloud KMS
- Container security: Trivy, Clair, Anchore
- Kubernetes security: kube-bench, kube-hunter, Falco, Kubesec
- CI/CD security: GitHub Actions security hardening, OPA/Gatekeeper, signed artifacts
- Monitoring & observability: Prometheus, Grafana, Elastic Stack
- Threat intelligence & modeling: OWASP Top Ten, MITRE ATT&CK

## Practical Projects & Exercises
- Build a small web app and add automated SAST and SCA checks to CI.
- Containerize the app, scan images with Trivy, and publish to a private registry.
- Deploy to a Kubernetes cluster and apply PodSecurityPolicies/PSA or OPA Gatekeeper policies.
- Implement secrets management for CI and runtime (e.g., Vault or cloud secret manager).
- Run a basic incident response tabletop: detect, contain, eradicate, recover.

## Learning Resources
- OWASP Top Ten: https://owasp.org/www-project-top-ten/
- MITRE ATT&CK: https://attack.mitre.org/
- Center for Internet Security (CIS) Benchmarks: https://www.cisecurity.org/
- Cloud provider security guides (AWS, Azure, GCP) and their well-architected/security frameworks

## Contribution
Contributions are welcome. To contribute:
1. Fork the repository.
2. Create a branch for your changes.
3. Add learning modules, exercises, or tooling guides.
4. Open a pull request describing your additions.

## License
This repository is open — add a license as appropriate.

---