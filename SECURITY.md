# Security Policy

## Overview

The Disruptor is a client-side educational game that runs in the browser. It does not collect, transmit, or store personal data, and has no user accounts or authentication systems. In Version 2, a Forge game sends its results for each year and the time played, with nothing personal, so that players can compare their results; other versions send nothing.

## Scope

Because the game runs in the browser from its own folder of files, the attack surface is small. There are no user accounts and no stored credentials. The only data the game sends is the anonymous Forge results described above.

The game does include:
- An optional Google Drive iframe for viewing the case study PDF
- Links to external resources (Creative Commons, GitHub)

## The CEO Reflection Tool (Katrien)

The game links to an optional reflection tool built on Claude artefacts, in which players can discuss their end-of-game report with the fictional CEO. Using it requires a free Claude account, and the player chooses to upload their own report PDF to Claude (Anthropic). The game itself sends nothing to the tool; anything shared with the tool is governed by Anthropic's terms and privacy policy, and players who prefer not to upload their report can simply skip the tool.

## For University IT and Data Protection Teams

The Disruptor processes **no personal data at all**: no accounts, no logins, no cookies. A Forge game sends its results for each year and the time played, with nothing personal; other versions send nothing. All play is anonymous. Game state exists only in the player's browser. Under GDPR there is nothing to assess — no personal data is collected, so no consent banner, DPIA, or processor agreement is needed. The full source code is public in this repository, so every claim can be verified by inspection. Institutions preferring zero network activity can download the game's folder and run it locally without a connection.

The one point of judgement is the optional Katrien reflection tool described above: a student who chooses to use it uploads their own game report to Claude under their own free account, in the same way they might paste text into any AI assistant. The game sends nothing to the tool itself, and the tool is entirely skippable.

## Reporting a Vulnerability

If you discover a security issue — for example, a cross-site scripting (XSS) vulnerability in the HTML, or a problem with how external content is loaded — please report it responsibly.

**Email**: ammon.salter@wbs.ac.uk

Please include:
- A description of the vulnerability
- Steps to reproduce it
- The potential impact
- Any suggested fix (optional but appreciated)

We will acknowledge receipt within 7 days and aim to address confirmed vulnerabilities promptly.

## What This Policy Does Not Cover

- Vulnerabilities in browsers, operating systems, or third-party services (Google Drive, GitHub Pages)
- Issues arising from user modifications to the source code
- Gameplay bugs (please use the bug report issue template for those)

Thank you for helping keep this project safe.
