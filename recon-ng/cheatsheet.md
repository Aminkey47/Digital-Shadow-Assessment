# Recon-ng Cheatsheet

## Starting Recon-ng

```bash
recon-ng
```

---

## Workspace Management

### List workspaces

```bash
workspaces list
```

### Create a workspace

```bash
workspaces create digital_shadow
```

### Select a workspace

```bash
workspaces select digital_shadow
```

### Delete a workspace

```bash
workspaces remove digital_shadow
```

---

## Marketplace

### View all available modules

```bash
marketplace search
```

### Search for specific modules

```bash
marketplace search github
```

```bash
marketplace search whois
```

```bash
marketplace search dns
```

### Install a module

```bash
marketplace install recon/domains-hosts/bing_domain_web
```

### Update installed modules

```bash
marketplace refresh
```

---

## Modules

### Load a module

```bash
modules load recon/domains-hosts/bing_domain_web
```

### Unload the current module

```bash
modules unload
```

### Show loaded module information

```bash
info
```

---

## Module Options

### View module options

```bash
options list
```

### Set the target

```bash
options set SOURCE example.com
```

### Set another option

```bash
options set <OPTION_NAME> <VALUE>
```

---

## Running Modules

```bash
run
```

---

## Viewing Collected Data

### Show domains

```bash
show domains
```

### Show hosts

```bash
show hosts
```

### Show contacts

```bash
show contacts
```

### Show companies

```bash
show companies
```

### Show credentials

```bash
show credentials
```

---

## Database

### Display all tables

```bash
db schema
```

---

## Help

### General help

```bash
help
```

### Help for a specific command

```bash
help workspaces
```

```bash
help modules
```

```bash
help marketplace
```

---

## Exit Recon-ng

```bash
exit
```
