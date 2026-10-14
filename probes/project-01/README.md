# Project 01: Kubernetes Probe Troubleshooting

## Objective

Practice diagnosing and resolving Kubernetes application health-check
issues using Deployments, Services, and liveness probes.

## Skills Practiced

- Kubernetes Deployments and Pods
- Liveness probe configuration
- Service configuration
- `kubectl` troubleshooting
- YAML validation and manifest management
- Root cause analysis (RCA)
- Git version control

## Project Structure

```text
project-01/
├── README.md
└── manifests/
    ├── app-deployment.yaml
    ├── app-service.yaml
    └── liveness.yaml
cat > probes/project-01/README.md <<'EOF'
# Project 01: Kubernetes Probe Troubleshooting

## Objective
Practice diagnosing Kubernetes application health-check issues using Deployments, Services, and liveness probes.

## Skills Practiced
- Kubernetes Deployments and Pods
- Liveness probe configuration
- Service configuration
- kubectl troubleshooting
- YAML validation
- Root cause analysis (RCA)
- Git version control

## Project Structure
project-01/
├── README.md
└── manifests/
    ├── app-deployment.yaml
    ├── app-service.yaml
    └── liveness.yaml

## Lab Workflow
1. Review manifests before applying them.
2. Deploy the application in a test Kubernetes cluster.
3. Inspect Pod status, events, and container logs.
4. Investigate probe failures and identify the root cause.
5. Apply a corrective change and verify recovery.
6. Document evidence, resolution, and lessons learned.

## Useful Commands
- kubectl get deployments,pods,services
- kubectl describe pod <pod-name>
- kubectl logs <pod-name>
- kubectl get events --sort-by=.metadata.creationTimestamp
- kubectl rollout status deployment/<deployment-name>

## Evidence and Results
Document the initial symptoms, relevant logs and events, root cause, corrective action, verification results, and prevention recommendations.

## Status
Lab documentation is prepared. Update this section after completing and validating the lab.

## Environment
- Kubernetes: Record the cluster version
- Tools: kubectl and Git
- Lab type: Non-production practice environment
