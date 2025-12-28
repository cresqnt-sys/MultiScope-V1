> [!WARNING] 
> This repository has been archived in favor of [MultiScope V2](https://github.com/cresqnt-sys/MultiScope)

# <img src="biomescope.ico" alt="Project Logo" width="40" style="vertical-align: middle;"/>&nbsp;MultiScope


[![GitHub stars](https://img.shields.io/github/stars/cresqnt-sys/MultiScope?style=social)](https://github.com/cresqnt-sys/MultiScope/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/cresqnt-sys/MultiScope)](https://github.com/cresqnt-sys/MultiScope/issues)
[![GitHub last commit](https://img.shields.io/github/last-commit/cresqnt-sys/MultiScope)](https://github.com/cresqnt-sys/MultiScope/commits/main)
[![Discord](https://img.shields.io/badge/Discord-Join%20Chat-7289DA.svg?logo=discord&logoColor=white)](https://discord.gg/6cuCu6ymkX)
[![GitHub All Releases](https://img.shields.io/github/downloads/cresqnt-sys/MultiScope/total)](https://github.com/cresqnt-sys/MultiScope/releases)
![Static Badge](https://img.shields.io/badge/license-CC_BY--NC--ND_4.0-orange)

> **Short Description:** A Sols RNG Biome Macro made to detect changes across multiple accounts while ensuring no AFK kicks.

---

**MultiScope** is a Python application designed to track Biome Changes in Sols RNG across multiple accounts. | Formerly BiomeScope

## Features

*   **Multi-Account Management:** Configure and track multiple accounts.
*   **Biome/Event Detection:** Automatically detects biomes with sub second delays.
*   **Discord Notifications:** Sends notifications via Discord webhooks for configured events and accounts.
*   **Statistics Tracking:** Keeps track of detected events (e.g., biome counts) and session time.
*   **GUI:** Provides a tabbed interface for controls, webhooks, stats, logs, and settings.
*   **(Optional) Anti-AFK:** Includes functionality to prevent being marked as AFK Kicked. This is done without you even noticing.
*   **Configuration:** Saves settings, accounts, and logs.
*   **Update Checker:** Checks for new versions on startup.

## Getting Started

### Prerequisites

*   Python (or use the precompiled executable)

### Installation

**Option 1: Using Python**

1.  Clone the repository:
    ```bash
    git clone https://github.com/cresqnt-sys/MultiScope
    cd MultiScope 
    ```
2.  Install Python dependencies:
    ```bash
    # It's recommended to use a virtual environment
    python -m venv venv
    # Activate the virtual environment (Windows example):
    venv\\Scripts\\activate 
    # (macOS/Linux example): source venv/bin/activate

    # Install requirements
    pip install -r requirements.txt
    ```

**Option 2: Using Precompiled Executable**

1.  Download the precompiled executable from the releases section.
2.  Run the executable directly without any additional steps.

Note: The precompiled executable includes all necessary dependencies and does not require Python installation.

### Running the Project

```bash
# Ensure your virtual environment is activated (if used)
python main.py 
```

## Usage


1.  Launch the application using `python main.py`.
2.  Use the 'Manage Accounts' button to add your accounts.
3.  Use the 'Webhooks & Control' tab to add Discord webhook URLs.
4.  Configure which accounts notify which webhooks.
5.  Use the 'Configure Biomes' button to set up notification preferences. 
6.  Press F1 (or the 'Start' button) to begin detection.
7.  Press F2 (or the 'Stop' button) to stop detection.
8.  Monitor logs and stats in the 'Stats & Logs' tab.

## Changelog

Notable changes to this project are documented in the [CHANGELOG.md](CHANGELOG.md) file. The current version is **0.9.9-Stable**.

## License

This project is licensed under the **Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International** - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

*   **Created by:** cresqnt & Bored Man
*   **Original Inspiration:** Maxstellar

## Contact

*   **Discord Server:** [Join the MultiScope Discord](https://discord.gg/6cuCu6ymkX)
*   **GitHub Repository:** [https://github.com/cresqnt-sys/MultiScope](https://github.com/cresqnt-sys/MultiScope)

If you find MultiScope useful, please consider starring the repository on GitHub
