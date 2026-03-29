# Midnight Deep Visual Studio Theme

⚫ **Midnight Deep** is an original dark theme for **Visual Studio 2019, 2022, and 2026**. For something lighter, check out [🌌 **Midnight Lights**](https://marketplace.visualstudio.com/items?itemName=AustinStanding.vsthememidnightlights).

Now includes experimental support for **SQL Server Management Studio 19, 20, 21 and 22**!
> Note: [SSMS does not officially support third-party extensions at this time](https://learn.microsoft.com/en-us/ssms/faq#are-extensions-supported-in-ssms).

![Midnight Deep Screenshot](https://github.com/austinstanding/midnight-deep-vstheme/raw/master/images/screenshot1.png)

Midnight Deep draws from the palette of Midnight Lights, while providing a true hex #000000 background and lower brightness generally. This won't be for everyone or every occasion, but my vision is to provide an after hours theme that will let your eyes find rest even when you can't.

## Installation

After [installing the extension from the Marketplace](https://marketplace.visualstudio.com/items?itemName=AustinStanding.vsthememidnightdeep), the theme will be available in the dropdown under *Tools -> Theme* or *Tools -> Options -> General*.

For SSMS 21+, simply open the .vsix file to install via the VSIX Installer.

## Misc

CI/CD uses Azure DevOps, following [Meziantou's Blog](https://www.meziantou.net/ci-cd-pipeline-for-a-visual-studio-extension-vsix-using-azure-devops.htm). CD presently disabled as VsixPublisher does not support the Themes category.

With introduction of breaking changes or new themed features previous elements are kept for backwards compatibility.

### For SSMS 19 & 20

> Note: custom themes will face the same issues as the incomplete Dark theme implementation.

<!-- Adapted from https://elasticjobsmanager.azureops.org/docs/installation.html -->

- Extract the .vsix file in a folder named `Midnight Deep Theme` using 7zip
- Copy this folder to the location (subbing the correct version number) `C:\Program Files (x86)\Microsoft SQL Server Management Studio 20\Common7\IDE\Extensions`; You will need admin permissions to do this
- Restart SSMS
- You will now see theme available

## Release Notes

### v2.1

- Add experimental support for SQL Server Management Studio 🧪
- Add 2026 fallback to standard dark theme ➕

### v2.0

- Add support for VS2026 🔧
- Tweak keyword colorization 🚧
