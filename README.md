# .github

This is a special repository that provides default community health files and templates for all repositories in the **Ticiyo** organization.

## What is this repository?

The `.github` repository is a special repository recognized by GitHub. When placed at the organization level, it allows you to define default files that will be used across all repositories in the organization that don't have their own versions of these files.

## Purpose

This repository serves as a central location to:

- 📋 Define default issue and pull request templates
- 📝 Provide organization-wide community health files
- 🤝 Establish consistent contributing guidelines
- 📖 Set up default documentation standards
- 🔒 Configure default security policies
- 💬 Define discussion templates and categories

## Supported Files

You can add the following files to this repository, and they will be used as defaults across all repositories in the organization:

### Community Health Files

- `CODE_OF_CONDUCT.md` - Code of conduct for all projects
- `CONTRIBUTING.md` - Guidelines for contributing to projects
- `SECURITY.md` - Security policy and vulnerability reporting instructions
- `SUPPORT.md` - Support resources and how to get help
- `FUNDING.yml` - Funding and sponsorship information

### Templates

- `.github/ISSUE_TEMPLATE/` - Default issue templates
- `.github/PULL_REQUEST_TEMPLATE.md` - Default pull request template
- `.github/DISCUSSION_TEMPLATE/` - Default discussion templates

### Workflows (Optional)

- `.github/workflows/` - Reusable GitHub Actions workflows

## Benefits

✅ **Consistency** - Ensure all repositories follow the same standards  
✅ **Efficiency** - Set up once, apply everywhere  
✅ **Maintenance** - Update defaults in one place  
✅ **Onboarding** - New repositories automatically get proper documentation  

## How It Works

When someone opens an issue, creates a pull request, or views community guidelines in any repository under the Ticiyo organization:

1. GitHub first checks if the file exists in that specific repository
2. If not found, GitHub looks for the file in this `.github` repository
3. If found here, it uses these default files

## Contributing

To add or update default files for the organization:

1. Create a new branch
2. Add or modify the appropriate files
3. Submit a pull request for review
4. Once merged, changes will apply to all organization repositories

## Learn More

For more information about `.github` repositories, visit:
- [GitHub Documentation: Creating a default community health file](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)

---

*This repository helps maintain consistency and quality across all Ticiyo projects.*