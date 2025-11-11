---
name: Dependabot Security Alert
about: Security vulnerability detected by Dependabot
title: 'Security: [Dependency name] vulnerability'
labels: ['security', 'dependencies', 'dependabot']
assignees: ''
---

## Security Alert

Dependabot has detected a security vulnerability in one of our dependencies.

### 🚨 Critical Information
- **Dependency**: {{ dependencyName }}
- **Severity**: {{ severity }}
- **Affected versions**: {{ vulnerableVersions }}
- **Patched versions**: {{ patchedVersions }}
- **CVE**: {{ cve }}

### 📋 Action Required
- [ ] Review the vulnerability details
- [ ] Test the updated dependency in a development environment
- [ ] Update the dependency to a patched version
- [ ] Verify functionality after update
- [ ] Deploy to production after testing

### 🔍 Additional Context
Add any relevant context about how this dependency is used in the project.

### 🧪 Testing Notes
- [ ] Core Drupal functionality works
- [ ] Custom modules function correctly
- [ ] Theme styling remains intact
- [ ] No performance regressions

### 📚 Resources
- [GitHub Security Advisory]({{ advisoryUrl }})
- [Dependency Documentation]({{ dependencyUrl }})