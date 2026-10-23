# Operation Risk Register

A lightweight, browser-based tool for documenting and managing operational risks. The register captures risk details and supports assessment, mitigation planning, and CSV export.

## Features

- Record risk event number, department, process, title, description, and causes.
- Classify operational risk events and describe existing mitigators.
- Assess impact, impact type, likelihood, and current net risk rating.
- Choose a mitigation strategy, record acceptance authority, and assign an action plan, target, and owner.
- Add, edit, and delete risk entries; edit table cells directly or double-click a row to load it into the form.
- Export the register as `Risk_Register.csv`.
- Automatically save and restore entries using browser local storage.

## Getting started

1. Download or clone this repository.
2. Open `risk2.html` in a modern web browser.
3. Enter a Risk Event No. and the relevant risk details, then select **Add Risk**.
4. Use **Edit** or **Delete** to manage entries, and **Export CSV** to download the register.

No server or package installation is required.

## Data storage

Risk entries are stored in the browser's local storage for the current browser profile. They are not uploaded to a server and are not automatically shared between browsers or devices. Export a CSV backup when you need to transfer or retain a copy of the register.

## Technology

Built with HTML, CSS, and vanilla JavaScript.
