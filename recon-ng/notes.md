# Recon-ng Notes

## Introduction

 I explored Recon-ng to learn a more modular approach to Open Source Intelligence (OSINT). Unlike SpiderFoot, which automatically runs multiple data sources, Recon-ng allows the user to choose specific modules depending on the type of information being collected.

---

## Setting Up Recon-ng

Recon-ng was already available in Kali Linux, so no manual installation was required.

To start Recon-ng:

```bash
recon-ng
```

This launched the interactive workspace where all reconnaissance activities are performed.

---

## Understanding Workspaces

Recon-ng stores data inside workspaces.

To create a workspace:

```bash
workspaces create digital_shadow
```

To switch workspaces:

```bash
workspaces select digital_shadow
```

Keeping separate workspaces makes investigations organised and prevents mixing results from different targets.

---

## Exploring the Marketplace

Recon-ng uses modules that can be installed from its Marketplace.

Useful commands:

```bash
marketplace search
marketplace search github
marketplace install
```

I learned that Recon-ng is very different from SpiderFoot because it only performs tasks after the required module has been installed and loaded.

---

## Loading Modules

Modules are loaded using:

```bash
modules load <module_name>
```

Each module performs a different task such as:

- Finding subdomains
- Looking up hosts
- Collecting contacts
- Searching GitHub
- Gathering DNS information

---

## Running Reconnaissance

Before running a module, required options must be configured.

Example:

```bash
options list
options set SOURCE example.com
run
```

The SOURCE option tells the module which target to investigate.

---

## Challenges I Encountered

- Understanding the Recon-ng command structure.
- Learning the difference between workspaces, modules and marketplace.
- Finding which modules required API keys.
- Understanding that not every module works without additional configuration.

---

## Lessons Learned

Recon-ng is more flexible than SpiderFoot because it allows investigators to choose exactly which reconnaissance modules to execute.

I also learned:

- How Recon-ng organises investigations using workspaces.
- How modules are installed and loaded.
- How reconnaissance results are stored.
- That some modules require API keys while others work immediately.
- The importance of modular reconnaissance during OSINT investigations.

---

## Reflection

Recon-ng showed me that professional OSINT tools are highly modular. Rather than relying on one large scan, investigators can combine specialised modules to collect targeted intelligence. This provides greater control over the reconnaissance process and produces more focused results.
