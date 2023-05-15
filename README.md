A collection of architectural decision records
# Operating model
- [OPM-1: Decision tracking](operating-model/1-decision-tracking.md)
- [OPM-2: Limit Team Size](operating-model/2-limit-team-size.md)
- [OPM-3: Define Team Principles](operating-model/3-define-team-principles.md)
- [OPM-4: Team Design Phase](operating-model/4-team-design-phase.md)
- [OPM-5: Microservice Ownership](operating-model//5-microservice-ownership.md)

# Infrastructure
- [INF-1: Infrastructure as code](infrastructure/1-infrastructure-as-code.md)
- [INF-2: Use Terraform for Infrastructure Changes](infrastructure/2-use-terraform.md)
- [INF-3: Use a CICD Pipeline for Infrastructure Changes](infrastructure/3-cicd-infrastructure.md)
- [INF-4: Use Github Actions for CI/CD Pipelines](infrastructure/4-github-actions-cicd.md)
- [INF-5: Use Github for Code Management](infrastructure/5-use-github.md)
- [INF-6: Host Microservices in AWS](infrastructure/6-use-AWS.md)
- [INF-7: One Repository Per Environment](infrastructure/7-one-repo-per-env.md)
- [INF-8: Use a Managed Kubernetes Service](infrastructure/8-use-EKS.md)
- [INF-9: Deploy Microservices Using a GitOps Deployment Tool](infrastructure/9-use-gitops-tool.md)
- [INF-10: Implement a Traefik Ingress Controller](infrastructure/10-trafek-ingress.md)
- [INF-11: Use Shared and Managed Database Services](infrastructure/11-use-shared-managed-DB.md)
# Microservice Design
- [MSD-1: Use Standard Design Process](microservice-design/1-use-standard-design-process.md)
- [MSD-2: Scope Design Using Key Actors](microservice-design/2-scope-design-using-key-actors.md)
- [MSD-3: Use Jobs as the Unit of Analysis](microservice-design/3-use-jobs-for-analysis.md)
- [MSD-4: Use the Standard Job Story Format](microservice-design/4-use-job-story-format.md)
- [MSD-5: Use PlantUML to Discover Interaction Patterns](microservice-design/5-use-plantUML.md)
- [MSD-6: Seperate Service Endpoints into Commands and Queries](microservice-design/6-separate-commands-queries.md)
- [MSD-7: Colect Feedback on your Service Designs](microservice-design/7-collect-feedback.md)
- [MSD-8: Web APIs are Layered on Top of Microservices](microservice-design/8-web-apis-on-top.md)
- [MSD-9: Use Event Storming Instead of Formal DDD](microservice-design/9-use-event-storming.md)
- [MSD-10: Microservices Can Share Physical Database Clusters](microservice-design/10-share-db-clusters.md)


# Microservice Engineering
- [MSE-1: Avoid Microservices Calling Each Other Directly](microservice-engineering/1-intra-MS-communication.md)
- [MSE-2: Use Redis to Implement the Reservations Database](microservice-engineering/2-redis-for-reservations.md)
- [MSE-3: Start Microservices with Reusable Templates](microservice-engineering/3-start-with-templates.md)
- [MSE-4: Starting Microservices from Reusable Templates](microservice-engineering/4-healthcheck-template.md)
- [MSE-5: Use Faux Git Submodules](microservice-engineering/5-faux-git-submodules.md)
