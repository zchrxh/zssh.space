Welcome to **zssh.space**, a collection of self-hosted services.

## The Name
zssh.space is made up of two components, the domain name (zssh) and the top-level domain (.space). 'zssh' is a portmanteau of Zsh (Z shell) and SSH (the network protocol), and the top-level domain, '.space', was chosen because space is cool. 🪐

## The Services
Currently, I am not accepting sign-ups on access-restricted services (e.g., Jellyfin, Navidrome, etc) from people I don't know personally. If I had enough server resources to handle many requests from unmonitored users across the world, I would be allowing people to sign up. Sadly, I do not.
- [Jellyfin](https://jelly.zssh.space)
- [Navidrome](https://navi.zssh.space)
- SearXNG (this service is being discontinued, sorry)

## The Hardware
zssh.space is primary hosted on a Dell OptiPlex 7090 Micro that sits in my living room running Proxmox VE. Here's the specs if you're interested:

**CPU:** Intel Core i5-11500T @ 3.90 GHz\
**GPU:** Intel UHD Graphics 750 @ 1.20 GHz (integrated)\
**Memory:** 16 GB DDR4

### Storage
- Root: 512 GB M.2 NVMe SSD
  - PVE OS: 96 GB
  - PVE Swap: 8 GB
  - ... (the rest goes to virtual machines and containers)
- Media: 4 TB 2.5" SATA SSD
