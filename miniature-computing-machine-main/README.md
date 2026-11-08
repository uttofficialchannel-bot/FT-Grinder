# TNStats Automation Hub

A collection of Playwright-based browser automation runners, GitHub Actions workflows, and custom injection scripts for managing automated tasks and tracking live channel statistics.

## Project Structure

* **`runner.js`**: Playwright runner script that launches a headless Chromium instance, injects local storage, visits target URLs, and evaluates custom scripts.
* **`script.js`, `script2.js`, `script3.js`**: Custom client-side injection scripts for automated task loops, button clicking, challenge math solvers, and API command triggers.
* **`controls.html`**: Local web UI control panel for generating GitHub Actions workflow dispatch commands.
* **`index.html`**: Live channel statistics dashboard powered by public data feeds and filtered via `channels.json`.
* **`.github/workflows/`**: Automation pipelines (`run-script.yml`[cite: 11] and `main.yml`[cite: 12]) for cloud execution.