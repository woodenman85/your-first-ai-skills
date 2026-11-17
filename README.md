# Your First AI Skills

This companion helps you try a skill in Claude Code or Codex and check the result. Start in a practice folder you can reset. Pick one kit and open its instructions.

| Kit | What you'll make | What you'll need |
| --- | --- | --- |
| [Build a small website](kits/website.md) | A cleaner version of a fictional bakery page | Claude Code or Codex and a browser |
| [Make a short video](kits/video.md) | A five-second title card | Claude Code or Codex and a compatible HyperFrames setup |
| [Research a website](kits/research.md) | A short summary you can check against a public source | Claude Code or Codex and Firecrawl access |

[Connect a browser](browser.md) if you want your assistant to work in a browser tab. This is optional for the first exercise.

## Start here

1. Open this repository on GitHub. You can read public files without an account. If you want to star or fork it, [create an account](https://docs.github.com/en/get-started/start-your-journey/creating-an-account-on-github) and verify your email.
2. Use **Code → Download ZIP**, extract the archive, and open that folder as a project in your assistant. For Claude Code, start Claude Code from that folder. For Codex, open the folder in the app or start the CLI there. [Claude Code quickstart](https://code.claude.com/docs/en/quickstart) · [Codex skills](https://learn.chatgpt.com/docs/build-skills)
3. Choose a kit and paste its setup prompt into the assistant. Replace `<kit-file>` with the file path shown on that kit page.
4. Review the source, version, install path, and prerequisites the assistant reports. After installation, start a new session if the skill does not appear, then try the exercise.

## Setup prompt

> Read README.md and <kit-file> in this practice folder. Help me set up this kit for the assistant I am using. Before changing anything, show me the official upstream source, the release or commit you reviewed, the exact skill folder, and the local install path. Check the README, license, SKILL.md, and any referenced scripts. Tell me which dependencies, accounts, or permissions are needed. Use the documented project installation for this assistant and preserve existing installs. Wait for me before adding optional hooks, tools, accounts, or browser access. After setup, tell me how to invoke the skill, run the practice exercise, and show me what to check and how to undo the install.

Save the source URL, version, and install path that the assistant reports. When removing a skill, use the documented uninstall route or remove only the project skill folder you added. Start a fresh session and check that the skill no longer appears.

Check the upstream install instructions for your assistant and version before starting a kit. Availability and requirements can vary by platform.
