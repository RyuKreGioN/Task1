# Task1
New Repos

## 1. Tools Installed

The following modern development and AI-agent tools were successfully integrated into the workspace:

* *Cursor IDE (v0.x.x):* An AI-first code editor fork of VS Code, utilized as the primary environment for coding, file management, and terminal execution.
* *Claude Code Add-on:* Anthropic's agentic AI assistant integrated into the IDE to facilitate contextual codebase understanding, file creation, and intelligent command execution.
* *Codex Add-on:* OpenAI's coding model integration utilized for side-by-side programming support, inline suggestions, and syntax analysis.
* *Git & GitHub:* Utilized for local version control, repository initialization, tracking modifications, and pushing assets to the cloud.

---

## 2. Steps Completed

The environment setup was executed through the following sequential phase workflow:

1.  *IDE Installation:* Downloaded and installed the Cursor editor executable onto the local system, initializing standard configurations.
2.  *Extension Acquisition:* Navigated to the built-in Extensions Marketplace within Cursor to locate and download the verified Claude Code and Codex add-ons.
3.  *Authentication & Linking:* Initialized the extensions, executing the cloud authentication workflow to link the local IDE environment with respective developer API profiles.
4.  *Repository Setup:* Formulated a public-facing repository on GitHub to host project documentation.
5.  *Workspace Localization:* Cloned the online GitHub repository locally and mapped the directory path directly into the Cursor workspace workspace view.
6.  *Documentation Drafting:* Formulated this README.md file inside the local workspace path to break down technical steps and workflow adjustments.
7.  *Version Deployment:* Executed Git stage (git add), local commit (git commit), and remote deployment (git push) protocols to update the live GitHub directory.

---

## 3. Issues Ran Into & How They Were Solved

During the setup phase, a few operational constraints required active troubleshooting and adaptation:

### Issue 1: Missing "Sign-In" UI Elements
* *The Problem:* Upon downloading both the Claude Code and Codex extensions, no distinct login UI buttons or pop-up redirects appeared within the extension overview panel, leaving the integrations temporarily unauthenticated.
* *The Solution:* Leveraged IDE shortcuts to open the global Command Palette (Ctrl + Shift + P / Cmd + Shift + P). Manually ran explicit activation calls (e.g., searching for extension-specific focus and activation triggers). This successfully forced the editor to render the OAuth redirection web links and log into the accounts.

### Issue 2: Terminal Execution Paths
* *The Problem:* Initial attempts to call extension processes directly inside the basic editor terminal resulted in unrecognized paths due to localized environment variable updates.
* *The Solution:* Restarted the Cursor terminal instance entirely to force-refresh local path paths. Verified connection status using standard diagnostics to ensure full communication between the editor and the cloud models.
