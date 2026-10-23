# Assay

Assay compares AI-training platforms (Outlier, Mercor, Scale AI, DataAnnotation and others) on funding, pay, domains, geography and eligibility, so you can decide where specialists earn the most with the least friction.

Every value it shows carries its source and date. Anything no trusted source has stated stays blank instead of being guessed. It needs no account, no API keys and no paid services, and it runs entirely on your computer.

This repository holds the Windows installers and the update feed. The app checks here for new versions.

## Install

1. Download `Assay-Setup-<version>.exe` from the [latest release](https://github.com/ultra-wizard/assay-releases/releases/latest).
2. Run it. It installs for your account only and needs no administrator rights.
3. The installer is not signed yet, so Windows may say **Windows protected your PC**. Choose **More info**, then **Run anyway**. You only do this once.

Assay needs Windows 10 or 11 (64-bit).

## Using it

- Assay opens with data gathered when the release was built, then refreshes it from public sources on its own.
- Closing the window keeps Assay in the tray, still refreshing and sending notifications. Quit from the tray icon. **Start with Windows** in the same menu starts it when you sign in.
- Updates download in the background. Choose **Restart to update**, or the update installs the next time you quit.
- The Help page inside the app explains every screen.

## Your data

Your decisions, notes, settings and the database stay on your computer in `%APPDATA%\Assay`. Nothing is sent anywhere except the requests Assay makes to public websites to read their data, which identify themselves as Assay with a link to this page. Uninstalling keeps your data; delete that folder to remove it.

## Requests to your site

If you run a site Assay reads and want it to stop, or want to ask about anything else, email ultra.wizard@hotmail.com. Assay follows robots.txt and waits between requests to the same host.

## Problems

If Assay cannot start, it shows a window with Retry and names its log, `%APPDATA%\Assay\logs\server.log`. Include that file when you report a problem by email.
