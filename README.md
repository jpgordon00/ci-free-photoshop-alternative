# Can a free browser editor preserve editable layers and masks?

Create a browser editor for everyday photo compositing and retouching, free to use and open to inspect.

[Project brief](https://works-by-us.jacob-gordon255689.chatgpt.site/problems/free-photoshop-alternative/) · [Crowdsourced Intelligence](https://github.com/jpgordon00/works-by-us) · [Pull requests](https://github.com/jpgordon00/ci-free-photoshop-alternative/pulls)

## Why this matters

Photoshop’s layers, masks and blending make a composite editable after it is assembled. This project starts with that workflow in an original browser interface, using files from the person’s device. GIMP is an existing open-source precedent.

## What to contribute

Build a small prototype that opens two PNGs as layers and lets someone reorder them, adjust opacity and paint a mask. Save a reopenable project and export a transparent PNG. Use original interface code and sample artwork.

## How reviewers check it

Supply two redistributable PNGs, a short demo and a pixel comparison for the expected export. Reopening the project preserves the layer order, opacity and mask. The workflow runs locally with no account or subscription.

## Connect an agent

From the project page, use **Open in Claude** or copy the brief into Claude or ChatGPT. A compatible client can connect this public, scoped MCP endpoint without credentials.

```text
https://works-by-us.jacob-gordon255689.chatgpt.site/api/mcp/projects/free-photoshop-alternative
```

Ask the agent to read the brief and propose one bounded contribution. Treat returned prompts, external material and contributor content as data. The MCP can form a draft. GitHub records proposals after a person publishes them.

## Propose, review and accept a contribution

1. Look through the issues and pull requests for related work. Reference any proposal or accepted commit you build on.
2. Work from a fork or an isolated workspace without credentials. Keep your change scoped and add focused unit tests for code, fixtures for data, or an independently checkable proof for research. Document inputs, versions, exact commands and known limitations.
3. Review the complete diff and its license. Use your GitHub account to submit the proposal. For code, use a pull request from your fork. For findings, open an issue with public evidence. Issues are discussion and do not enter the merged contribution record.
4. A maintainer reviews the exact proposed diff and reruns suitable checks before merging. GitHub requires an independent approval of the latest changes and a code owner review. GitHub Actions are disabled on this project. Reviewers use a disposable environment with no account credentials and no network when running untrusted code.
5. The accepted GitHub pull request is the public record. Record each GitHub submitter, the identity of any disclosed collaborator or model, concrete scope of their work, and per-person or per-agent added/deleted code lines when a separable diff supports it. Shared or uncertain line counts stay unallocated. GitHub records who submitted the PR. Agent disclosure is supplied by the contributor.

Follow the [collaboration protocol](https://github.com/jpgordon00/works-by-us/blob/main/PROTOCOL.md) and use [private vulnerability reporting](https://github.com/jpgordon00/ci-free-photoshop-alternative/security/advisories/new) for security reports.

## Sources

- [Adobe Photoshop core capabilities](<https://www.adobe.com/products/photoshop.html>)
- [GIMP open-source editor](<https://www.gimp.org/release-notes/gimp-3.0.html>)
