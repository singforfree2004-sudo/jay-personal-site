# Deployment Notes

Last updated: 2026-05-04

## Goal

Make Jay's personal website update automatically through:

```text
GitHub -> Netlify
```

After setup, Jay can ask Frank to update the site. Frank can edit files, commit changes, push to GitHub, and Netlify will redeploy automatically.

## Current Local Project

```text
/Users/chih-chiehhsu/Documents/CodexWorkspace/projects/jay-personal-site
```

## Current Status

- Website files imported from `jay_site_v4_interactive.zip`.
- Netlify config exists: `netlify.toml`.
- Local Git repository created.
- GitHub repository connected:
  `https://github.com/singforfree2004-sudo/jay-personal-site`
- Netlify production URL:
  `https://animated-panda-03c39b.netlify.app/`
- `sitemap.xml` uses the production Netlify URL.

## One-Time Setup Completed

Completed account steps:

1. GitHub account authorization.
2. GitHub repository creation.
3. GitHub push from local project.
4. Netlify connection to GitHub repository.
5. Netlify production deployment.

Frank can guide and execute the technical steps where permission is available.

## Recommended GitHub Repository

```text
jay-personal-site
```

Actual GitHub repository:

```text
https://github.com/singforfree2004-sudo/jay-personal-site
```

Recommended visibility:

```text
Public
```

Reason:

- GitHub Pages is not required, but public is simplest for a personal website.
- Netlify can also deploy private repos if the free plan and authorization allow it.

## Recommended Netlify Settings

Build command:

```text
leave blank
```

Publish directory:

```text
/
```

Reason:

- This is a plain static website.
- `index.html` is already at the project root.

Actual production URL:

```text
https://animated-panda-03c39b.netlify.app/
```

## Update Workflow

When Jay asks for an update:

1. Frank edits the website files locally.
2. Frank previews or checks the result.
3. Frank commits the change with Git.
4. Frank pushes to GitHub after Jay confirms.
5. Netlify automatically deploys.
6. Frank checks or asks Jay to confirm the deployed result.

## Netlify Drop Backup

If GitHub/Netlify auto deploy is not set up yet:

1. Frank can edit the local site.
2. Frank can prepare a clean deploy folder or zip.
3. Jay can upload it with Netlify Drop.

This is useful as a temporary fallback, but not recommended as the main long-term process.
