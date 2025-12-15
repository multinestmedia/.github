# .github Repository

This repository contains organization-level configuration files for the **Multinest Media** GitHub organization.

---

## Purpose

GitHub automatically applies files in this repository across all repositories in the organization that don't have their own versions. This provides centralized, consistent defaults for:

- Community health files
- Issue and pull request templates
- Organization profile content

---

## Contents

### Community Health Files

- **`CODE_OF_CONDUCT.md`** – Standards for community participation and enforcement policies
- **`CONTRIBUTING.md`** – Guidelines for external contributions and eligibility requirements
- **`SECURITY.md`** – Vulnerability reporting process and security support policy

These files are automatically surfaced by GitHub in repositories that don't define their own versions.

### Templates

- **`pull_request_template.md`** – Default template for pull request descriptions
- **`ISSUE_TEMPLATE/bug_report.yml`** – Structured form for bug reports
- **`ISSUE_TEMPLATE/feature_request.yml`** – Structured form for feature requests

### Profile

- **`profile/README.md`** – Organization profile content displayed at `github.com/multinestmedia`

---

## How It Works

When contributors interact with repositories in this organization:

1. GitHub checks if the specific repository has its own community health files
2. If not found, GitHub falls back to the files in this `.github` repository
3. Templates and guidelines are automatically applied where appropriate

Individual repositories can override these defaults by including their own versions.

---

## Maintenance

This repository is maintained by Multinest Media.

Changes to these files affect the default behavior across all organization repositories. Updates should be:
- Reviewed carefully
- Tested for clarity and accuracy
- Documented in the `CHANGELOG.md`

---

## Resources

- [GitHub Community Health Files Documentation](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
- [Issue and Pull Request Templates](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests)

