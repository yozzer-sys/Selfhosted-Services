# Selfhosted Services

Here, I'll share the services and applications I host on my own servers.
Self-hosting provides more control over my data and privacy.

## Comprehensive Data Backup Strategy (6-4-2 with Self-Managed Cloud Storage - RAID6)
To ensure the safety and availability of my self-hosted services and data, I've implemented a comprehensive data backup strategy, emphasizing the 6-4-2 approach, further fortified with encryption:

- **6 Copies for Resilience**: I maintain a total of six copies of my data, which include the original files, data mirrored through a NAS with RAID1, two additional copies on external USB drives, and two secure cloud storage backups. This redundancy ensures data resilience and accessibility.

- **4 Types of Storage Media**: My data is distributed across four different types of storage media, encompassing the original files, an external USB drive, network-attached storage (NAS) with RAID1, and self-managed cloud storage with RAID6. This diversification minimizes the risk of data loss due to hardware failures.

- **2 Offsite Safeguards with Encryption**: In addition to on-site redundancy, I secure two offsite backups, with data stored in self-managed cloud storage, which includes RAID6 for enhanced redundancy. Importantly, all offsite backups are encrypted to guarantee the utmost data security and confidentiality.

This clarified 6-4-2 strategy, with encryption both on the backup side and within self-managed cloud storage with RAID6, is designed to ensure the preservation and accessibility of my self-hosted services and data while prioritizing the highest levels of data security and resilience.

## Services

- **Cloudflare Tunnel**: for Vaultwarden and Whoogle-Search
- **Vaultwarden**: [Link to Vaultwarden](https://github.com/dani-garcia/vaultwarden)
- **Pihole 6**: [Link to Pi-hole](https://pi-hole.net/)
- **Jellyfin**: [Link to Jellyfin](https://jellyfin.org/)
- **Plex**: [Link to Plex](https://www.plex.tv/)
- **Sonarr**: [Link to Sonarr](https://sonarr.tv/)
- **Radarr**: [Link to Radarr](https://radarr.video/)
- **Synology Cloud**: [Link to Synology Cloud](https://www.synology.com/en-global/dsm/packages/Synology_Cloud)
- **OpenVPN over cloak**: Hosted on a KVM VPS [Link to cloak]((https://github.com/cbeuw/Cloak))

# Docker

I also use the following Docker containers to manage my servers:

## Containers

- **Portainer**: Web-based Docker management interface for managing your Docker containers. [Portainer GitHub](https://github.com/portainer/portainer)
- **homarr**: Customizable browser's home page to interact with your homeserver's Docker containers (e.g. Sonarr/Radarr). [homarr GitHub](https://github.com/ajnart/homarr)
- **immich**: Self-hosted photo and video backup solution directly from your mobile phone. [immich GitHub](https://github.com/immich-app/immich)
- **Jellyseerr**: A fork of overseerr with Jellyfin support. [Jellyseerr GitHub](https://github.com/Fallenbagel/jellyseerr)
- **Mealie**: A self-hosted recipe manager and meal planner. [Mealie GitHub](https://github.com/mealie-recipes/mealie)
- **PairDrop**: Local file sharing in your browser, inspired by Apple's AirDrop. [PairDrop GitHub](https://github.com/schlagmichdoch/PairDrop)
- **Stirling-PDF**: Locally hosted web application that allows you to perform various operations on PDF files. [Stirling-PDF GitHub](https://github.com/Frooodle/Stirling-PDF)
- **Watchtower**: A process for automating Docker container base image updates. [Watchtower GitHub](https://github.com/containrrr/watchtower)
- **Whoogle-Search**: A self-hosted, ad-free, privacy-respecting metasearch engine. [Whoogle-Search GitHub](https://github.com/benbusby/whoogle-search)

Feel free to explore and use these self-hosted services and Docker containers to enhance your self-hosted setup. Make sure to read the documentation and follow the setup instructions provided in each project's repository.
