# TaskFlow API Documentation

Live URL: https://taskflow-ee7a8f0a.mintlify.app/

## Overview
This repository contains the official documentation for the TaskFlow API. The goal of this project was to create a developer-centric, high-performance portal that translates complex architectural constraints into an intuitive, seamless integration experience.

## Workflow & Methodology
To deliver this documentation, I followed a structured product-led approach:

* **API Analysis**: Conducted a deep dive into the TaskFlow API architecture, mapping resource hierarchies and operational constraints to ensure accurate documentation.
* **Prototyping & Testing**: Validated endpoint behavior and lifecycle states to ensure the information provided is deterministic and reliable for developers.
* **Documentation Architecture**: Designed a clear, logical structure that prioritizes developer experience (DX), focusing on reducing time-to-first-call (TTFC).
* **Implementation (Mintlify)**: Leveraged Mintlify for the deployment, ensuring a modern, fast, and responsive UI. 
    * *Note: I am also familiar with Docusaurus (an other static Doc site generators).*
* **CI/CD Deployment**: Configured the repository for automated deployment, ensuring that documentation updates remain synchronized with the product lifecycle.

## Technical Stack
* **Framework**: Mintlify
* **Language**: Markdown / MDX
* **Version Control**: Git / GitHub

---
*Built with focus on clarity, precision, and developer satisfaction.*

# Mintlify Starter Kit

Use the starter kit to get your docs deployed and ready to customize.

Click the green **Use this template** button at the top of this repo to copy the Mintlify starter kit. The starter kit contains examples with

- Guide pages
- Navigation
- Customizations
- API reference pages
- Use of popular components

**[Follow the full quickstart guide](https://starter.mintlify.com/quickstart)**

## AI-assisted writing

Set up your AI coding tool to work with Mintlify:

```bash
npx skills add https://mintlify.com/docs
```

This command installs Mintlify's documentation skill for your configured AI tools like Claude Code, Cursor, Windsurf, and others. The skill includes component reference, writing standards, and workflow guidance.

See the [AI tools guides](/ai-tools) for tool-specific setup.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview your documentation changes locally. To install, use the following command:

```
npm i -g mint
```

Run the following command at the root of your documentation, where your `docs.json` is located:

```
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing changes

Install our GitHub app from your [dashboard](https://dashboard.mintlify.com/settings/organization/github-app) to propagate changes from your repo to your deployment. Changes are deployed to production automatically after pushing to the default branch.

## Need help?

### Troubleshooting

- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`.

### Resources
- [Mintlify documentation](https://mintlify.com/docs)
