# Arch-Medic

Arch Medic is a powerful, user-friendly tool designed to quickly diagnose and fix common Arch Linux issues, ensuring your system stays running smoothly. With simple, guided options and safe recovery features, you can confidently repair your Arch installation without worry.


Arch Medic is a free and open-source, user-friendly utility designed to help Arch Linux users quickly diagnose and resolve common system issues. Whether you're dealing with broken packages, dependency issues, or failed services, Arch Medic provides a series of easy-to-use solutions to restore your system to optimal performance.

**Description**

Arch Medic is a comprehensive first-aid toolkit for Arch Linux. Built with both beginners and experienced users in mind, it provides a simple interface for diagnosing and fixing common Arch Linux problems. Arch Medic helps resolve issues like broken dependencies, failed updates, systemd service errors, and more. With its powerful set of recovery tools, Arch Medic helps ensure your Arch Linux system stays healthy and running smoothly.

**Table of Contents**

- Installation
- Usage
- Features
- Tests

**Installation**

To install and set up Arch Medic, follow these steps:

1. Clone or download the archmedic.sh script: You can either download the archmedic.sh file directly or clone the repository if it's hosted on a platform like GitHub.
2. Make the script executable: chmod +x archmedic.sh
3. Run the script: ./archmedic.sh

**Note:** Ensure that your system has sudo privileges for commands that require administrative access.

**Usage**

- Once installed, Arch Medic provides an interactive menu to troubleshoot and resolve issues. Here’s how to use it:

- Open your terminal.

- Navigate to the directory containing archmedic.sh.

- Run the script: ./archmedic.sh

The script will display a menu with various diagnostic and repair options. You can select from the following options:

- Check for missing dependencies.
- View logs (journalctl).
- Check for failed systemd units/services.
- Fix partial upgrades.
- Remove or reinstall corrupted packages.
- Downgrade a package.
- Install and use Timeshift for system restore points.
- Restore your system to a previous state using Timeshift.
- The script will guide you through the process, prompting for necessary input at each step.

**Features**

Arch Medic comes with a variety of features to help you keep your system in top condition:

Comprehensive System Checks:

- Check for missing dependencies and errors in your system’s package database.
- Review logs with journalctl and check for failed systemd units or services.

Package Management Tools:

- Fix partial upgrades or remove corrupt/conflicting packages.
- Reinstall key packages such as systemd, glibc, or any package causing issues.
- Downgrade a package to an earlier version if the latest update caused problems.

System Recovery Tools:

- Install Timeshift, a powerful tool for creating and restoring system snapshots, so you can restore your system to a previous working state if necessary.

Easy-to-Use Menu System:

- The menu provides clear, simple options for troubleshooting common issues with intuitive prompts.

Logs and Audit Trails:

- Optional logging features that help track changes made by the tool (ideal for auditing or tracking repairs).

**Tests**

All features of Arch Medic have been tested by a professional QA Tester to ensure they work as expected on a variety of Arch Linux systems.

**Legal Disclaimer**

Arch Medic is provided "as-is" and "as-available", without any express or implied warranties of any kind, including but not limited to the implied warranties of merchantability, fitness for a particular purpose, or non-infringement.

By using this program, you acknowledge and agree that:

**No Warranty:** The developer makes no guarantees or representations regarding the functionality or performance of the software. While every effort has been made to ensure the program functions as intended, there is no warranty, express or implied, that the software will be error-free or free from interruptions.

**Risk of Use:** You assume full responsibility for any risks associated with using Arch Medic. The software is intended for use as a tool to diagnose and address issues within an Arch Linux system; however, it is your responsibility to ensure you have adequate backups and precautions in place before using the program.

**No Liability:** The developer shall not be held liable for any damages arising from the use, misuse, or inability to use Arch Medic, including but not limited to data loss, system failures, hardware damage, software conflicts, or any other direct or indirect damages that may occur. This includes any consequences from following the recommendations or actions suggested by the program.

**Backup Recommendation:** It is strongly advised to always create backups of critical data and system settings before using any system maintenance or repair tools, including Arch Medic.

**Use at Your Own Risk:** By using this program, you agree that you are solely responsible for any outcomes resulting from its use. The developer expressly disclaims any liability for damages, losses, or legal consequences resulting from actions taken while using the software.

This disclaimer applies to the maximum extent permitted by applicable law. If any part of this disclaimer is found to be invalid or unenforceable, the remainder will continue in full force and effect.
