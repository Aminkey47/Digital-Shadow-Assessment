# Recon-ng Cheat Sheet

A quick reference for the commands I used during this project.

---

## Launch Recon-ng

```bash
./recon-ng
```

---

## Marketplace

Show available modules:

```bash
marketplace search
```

Search for a specific module:

```bash
marketplace search bing
```

Install a module:

```bash
marketplace install recon/domains-hosts/bing_domain_web
```

Remove a module:

```bash
marketplace remove <module_name>
```

---

## Workspaces

Show current workspace:

```bash
workspaces list
```

Create a workspace:

```bash
workspaces create <workspace_name>
```

Load a workspace:

```bash
workspaces load <workspace_name>
```

Delete a workspace:

```bash
workspaces remove <workspace_name>
```

---

## Loading Modules

Load a module:

```bash
modules load recon/domains-hosts/bing_domain_web
```

Display module information:

```bash
info
```

Show required options:

```bash
options list
```

Set an option:

```bash
options set SOURCE owasp.org
```

Run the module:

```bash
run
```

Unload the current module:

```bash
back
```

---

## API Keys

List configured API keys:

```bash
keys list
```

Add an API key:

```bash
keys add shodan
```

Remove an API key:

```bash
keys remove shodan
```

---

## Database

Show discovered domains:

```bash
show domains
```

Show hosts:

```bash
show hosts
```

Show contacts:

```bash
show contacts
```

Show companies:

```bash
show companies
```

---

## Help

General help:

```bash
help
```

Help for the current module:

```bash
info
```

---

## Exit

```bash
exit
```


