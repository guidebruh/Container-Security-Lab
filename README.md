## Container Security Lab

# Objective
The Container Security Lab is designed to teach best practices for building, securing, and testing containerized applications. The lab emphasizes vulnerability scanning and remediation both before deployment and within continuous integration (CI) workflows. Learners will containerize a sample Go web API, analyze code and dependencies for risks, and implement automated scans in both terminal/CLI and CI pipelines.

# Skills Learned
- Building and containerizing applications with Docker and Go.
- Conducting static application security testing (SAST), dynamic analysis (DAST), and software composition analysis (SCA) using industry-standard tools.
- Scanning container images for vulnerabilities using Snyk and Docker Scout, with remediation strategies.
- Integrating security scans into CI pipelines to automate vulnerability detection.
- Making risk-based decisions on vulnerability remediation and implementing threat modeling for containerized environments.

# Tools Used
- Docker: Application containerization, image building, and deployment.
- Go: Building web API for containerization and testing.
- Snyk: Static code, dependency (SCA), and container image vulnerability scanning.
- Docker Scout: Container image analysis and vulnerability remediation.
- GitHub Actions: CI/CD pipeline for automated security testing.
