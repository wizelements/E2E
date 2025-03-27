# Privacy Policy for E2E GPT Developer Tool

_Last Updated: March 27, 2025_

Welcome to the E2E GPT Developer Tool. This privacy policy outlines how your information is handled when using this tool, specifically regarding GPT Actions that interact with your development environment for testing and validation purposes.

---

## 1. Overview

This tool is designed for software developers who wish to validate project structure, authentication, deployment, and related features through a GPT interface. It interacts with locally hosted or tunneled endpoints but does **not collect**, **store**, or **transmit** personal data beyond the scope of development-related payloads.

---

## 2. What We Collect

The E2E GPT Developer Tool only processes the following **temporary** information for the purpose of code/project validation:

- File and folder names (e.g., `package.json`, `auth.js`)
- Code-related metadata (e.g., type of files, project structure)
- Simulated prompts or messages (for chat-based review)
- Public endpoints temporarily exposed by the user for testing

⚠️ **No personal data, credentials, secrets, or tokens should ever be included in any GPT message or tunnel interaction.**

---

## 3. How This Data Is Used

Data submitted via GPT Actions is only used for the following purposes:

- Project structure validation (e.g., `/progress/init`)
- Authentication implementation checks
- Membership, payment, and core logic analysis
- Deployment and environment review
- Final project audit (non-sensitive)

This data is not stored, tracked, or logged.

---

## 4. Third-Party Services

The E2E GPT Developer Tool itself uses no cookies, trackers, analytics, or third-party APIs. GPT interactions are subject to [OpenAI’s Terms of Use](https://openai.com/policies/terms-of-use) and data handling policies.

Any temporary tunneling service (e.g., Cloudflare Tunnel or LocalTunnel) is configured and controlled **by you**, the developer.

---

## 5. Data Storage & Retention

We do **not** store or retain any data from:

- Your local server
- Your GPT prompts
- The responses of your local endpoints

Data exists **only during the live GPT session** and is discarded immediately after.

---

## 6. Security

All exposed local endpoints used during validation are:
- Created and controlled by the developer
- Only accessible via a public tunnel you configure
- Recommended to be **temporary**, secured, and closed when not in use

We recommend you **do not expose actual sensitive services** via tunneling.

---

## 7. Developer Responsibility

You, the developer, are responsible for:
- Ensuring no sensitive information is exposed during use
- Properly configuring and closing public tunnels
- Reviewing generated code and recommendations before applying them

This tool is meant strictly for **local development support**, not production environments.

---

## 8. Contact

If you have questions or concerns about this policy or tool usage, please contact the developer or refer to the tool’s documentation repository.

---

**Thank you for using the E2E GPT Developer Tool responsibly.**
