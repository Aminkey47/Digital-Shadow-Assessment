# Notes

## Goal

The goal of using Recon-ng was to learn how a modular OSINT framework works and to perform passive reconnaissance against **OWASP**.

---

## Installation

I installed Recon-ng from source on Ubuntu by cloning the official repository. Since Recon-ng relies on Python packages, I created a virtual environment to keep the installation isolated from the system Python.

The installation completed successfully, and I was able to launch the framework from the terminal.

---

## Exploring the Marketplace

One of the first things I learned was that Recon-ng uses a Marketplace where modules can be searched, installed, updated, and removed.

This was different from many tools I had used before because Recon-ng starts with very few modules installed. Instead, I had to choose and install only the modules I needed.

This modular design makes the framework lightweight and flexible.

---

## Using Modules

I explored several reconnaissance modules and learned how to:

- Search for available modules.
- Install modules from the Marketplace.
- Load a module.
- Configure its options.
- Execute the module.
- Review the collected results.

Understanding this workflow was one of the most valuable lessons from using Recon-ng.

---

## Challenges

### Shodan API

I wanted to use the Shodan module, but it was initially disabled because the required Python dependency was missing.

After creating a virtual environment and installing the missing package, the module became available.

However, I discovered another limitation: my free Shodan account did not include the query credits required by the module. Although authentication was successful, searches returned a **403 Forbidden** error.

This taught me that installing a module is only part of the process—access to third-party services may still be restricted by API plans.

---

### Censys Authentication

I also explored the Censys integration.

After creating a Censys account, I found that the platform now provides Personal Access Tokens instead of the legacy API credentials expected by the Recon-ng module.

Because of this difference, I was unable to configure the module successfully.

This highlighted the importance of checking whether a tool's integrations are compatible with the current versions of external services.

---

## Lessons Learned

Working with Recon-ng taught me much more than simply running reconnaissance modules.

I learned how modular frameworks operate, how external APIs integrate with security tools, and how API limitations can affect an investigation.

More importantly, I learned that troubleshooting is a normal part of cybersecurity. Solving dependency issues and understanding service limitations were just as valuable as the reconnaissance itself.


