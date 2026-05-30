# TaskFlow API Documentation

**Live Documentation:** https://taskflow-ee7a8f0a.mintlify.app/
---

## **Project Overview**
This repository holds the technical documentation for the TaskFlow API. My goal was to build a developer-first portal that strips away the complexity of the API's architecture and focuses on what actually matters: how to integrate it as quickly and intuitively as possible.

## **Workflow & Methodology**
To deliver this project, I took a practical, product-oriented approach:

* **API Analysis**: I started by digging into the TaskFlow architecture to map out resource hierarchies, identifying exactly what a developer needs to know to get started.
* **Prototyping & Testing**: I validated the behavior of the endpoints and their lifecycles. **P.S.: I intentionally included a mock authentication doc to ensure the documentation covers security best practices right from the start.**
* **Documentation Architecture**: I structured the content logically, focusing on reducing the Time-to-First-Call (TTFC) so developers can move from documentation to their first successful API call without friction.
* **Challenges & Future Improvements**: With more time, I would focus on aligning the documentation aesthetics with the product's existing Design System, implementing interactive visual cues to improve code traceability and readability. I would also integrate more prominent **CTAs for Support and Community** channels to foster a stronger feedback loop. Additionally, I would implement a **dynamic troubleshooting guide** to map specific error codes, proactively addressing developer pain points.

## **How to run locally**
If you want to preview these docs on your machine, it is straightforward:

1. Prerequisites: Ensure you have Node.js installed.
2. Install the Mintlify CLI:
```bash
`npm i -g mint`
```
3. Start the server:
```bash
`mint dev`
```
4. View the site: Your browser will open the documentation at `http://localhost:3000`

## Technical Stack
* Framework: Mintlify
* Structure: Markdown / MDX
* Version Control: Git & GitHub
