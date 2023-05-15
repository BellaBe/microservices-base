# INF - 7: One repository per environment
Date: 15-05-2023
## Status 
Accepted

## Context
We'll need a strategy for managing our infrastructure code. We can create a "monorepo" and build all enviornments from it, or we can manage environment code independantally.

## Decision
We'll create a Github repository for each unique environment that we are supporting. This will allow teams to own and operate their own infrastructure repositories in the early development and test phases.

## Consequences
Maintaining multiple repositories will result in some significant synchronisation challenges. Teams will need to ensure that their environments are compatible with the production environment or problems will not be discovered until late in the testing stages.