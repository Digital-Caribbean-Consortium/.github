# .github

This is the special `.github` repository for the Digital Caribbean Consortium organization.

## Purpose

This repository serves several important functions:

1. **Organization Profile**: The `profile/README.md` file is displayed on our organization's GitHub overview page
2. **Community Health Files**: Default community health files (CODE_OF_CONDUCT.md, CONTRIBUTING.md, SECURITY.md) that apply across all repositories in the organization
3. **Shared Templates**: Issue and pull request templates that can be used across repositories
4. **Shared Workflows**: Reusable GitHub Actions workflows

## Structure

```
.github/
├── profile/
│   └── README.md              # Organization profile page
├── CONTRIBUTING.md            # Contribution guidelines
├── CODE_OF_CONDUCT.md         # Code of conduct
├── SECURITY.md                # Security policy
└── README.md                  # This file
```

## What Gets Applied Where

- **profile/README.md**: Appears on the organization's main GitHub page at https://github.com/Digital-Caribbean-Consortium
- **Community Health Files**: Apply as defaults to all public repositories that don't have their own versions
- **Templates and Workflows**: Can be referenced by other repositories in the organization

## Learn More

- [GitHub Documentation: Creating a default community health file](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
- [GitHub Documentation: Customizing your organization's profile](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile)
