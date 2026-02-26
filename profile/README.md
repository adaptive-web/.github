<div align="center">

![Adaptive Logo](https://www.adaptive.co.uk/themes/custom/awbs4/assets/adaptive-drupal-specialists-logo-notrans.png)

### Internal Tools & Resources

</div>

---

## Quick Links

| Tool | Purpose |
|------|---------|
| [Sentrix](https://github.com/adaptive-web/sentrix) | Drupal updates dashboard — track Dependabot PRs, test plans, security advisories |
| [Bagoftrix](https://github.com/adaptive-web/bagoftrix) | Jira activity feed and team workload tracking |
| [adaptive-phoenix](https://github.com/adaptive-web/adaptive-phoenix) | Company website repo |
| [New-Deployment-Scripts](https://github.com/adaptive-web/New-Deployment-Scripts) | Deployment automation |

---

## Key Processes

### Drupal Updates
1. Dependabot opens PRs for patch updates → auto-merge after CI passes
2. Minor/major updates → manual review in Sentrix
3. All updates go through dev → staging → production
4. Run test plan before merging to production

### Security
- Daily automated scans via GitLeaks
- Dependabot security alerts auto-triage in Sentrix
- Critical vulnerabilities → immediate patch, hotfix process

### Deployments
- Pantheon multidevs for all client work
- PRs deploy to multidev automatically
- Merge to main → deploys to dev environment
- Production deployments via tagged releases or manual promotion

---

## Where to Find Things

| What | Where |
|------|-------|
| Client site repos | `adaptive-web/<client-name>` |
| Shared scripts | [New-Deployment-Scripts](https://github.com/adaptive-web/New-Deployment-Scripts) |
| PR templates | `.github/PULL_REQUEST_TEMPLATE/` |
| Issue templates | `.github/ISSUE_TEMPLATE/` |
| Workflow configs | `.github/workflows/` |

---

## Need Help?

- **DevOps/Infra issues**: Slack `#devops` or create an issue here
- **Client site problems**: Check the relevant client repo first
- **Process questions**: Confluence or Slack `#engineering`

---

## External

- **Website**: [adaptive.co.uk](https://adaptive.co.uk)
- **Services**: Drupal development, managed hosting, DevOps consulting

---

<div align="center">

*Adaptive — Drupal specialists, DevOps practitioners, based in the UK*

</div>