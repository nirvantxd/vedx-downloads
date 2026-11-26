# VedX downloads

VedX is a Windows desktop life-planning app. This repository hosts public installer releases; the application source is maintained separately.

## Download

Get the latest Windows x64 installer from the [Releases page](https://github.com/nirvantxd/vedx-downloads/releases/latest):

- `VedX_0.1.0_x64-setup.exe` — standard setup installer
- `VedX_0.1.0_x64_en-US.msi` — Windows Installer package

Requires Windows 10 or 11 and WebView2. This early build is not code-signed, so Windows may show an unknown-publisher or SmartScreen warning.

## Data and AI

VedX uses Supabase for sign-in and cloud data. When you request an AI plan, the prompt and profile details are sent to Google's Gemini service through VedX's hosted function. Do not enter sensitive information into AI prompts.

This is an early release. Some areas are still being developed, and AI availability depends on the hosted service.
