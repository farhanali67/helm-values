# helm-values (TEST)

Test repository for Helm chart values files.

The DevOps Self-Service Agent Backend pushes auto-generated Helm values here.

## Structure

```
helmchart/
└── env/
    ├── dev/
    │   └── <app-name>.yaml
    ├── staging/
    │   └── <app-name>.yaml
    └── prod/
        └── <app-name>.yaml
```

## Auto-merge

For testing, enable auto-merge on PRs or manually merge them when the agent creates them.

You can also set up a branch protection rule with "Require pull request reviews" disabled and enable "Allow auto-merge" in repo settings.
