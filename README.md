# Selfhosted Services

Here, I'll share the services and applications I host on my own servers.
Self-hosting provides more control over my data and privacy.

## Data Backups

To ensure the safety and availability of my self-hosted services and data, I follow the 5-4-2 backup strategy:

5 Copies: I have the original data, an external USB drive backup, an internal HDD backup on my NAS, a USB SSD backup on my NAS, and a cloud storage backup. This totals five copies of my data.

4 Different Media: My data is stored on four different types of media or devices, including the original data, an external USB drive, internal HDD, and USB SSD.

2 Offsite Backups: I have two offsite backups, the USB SSD backup and the cloud storage backup. These offsite backups help protect your data in case of physical disasters at your primary location.

## Services

- **Cloudflare Tunnel**: Public access for Vaultwarden and Whoogle-Search
- **Vaultwarden**: [Link to Vaultwarden](https://github.com/dani-garcia/vaultwarden)
- **Pihole 6**: [Link to Pi-hole](https://pi-hole.net/)
- **Jellyfin**: [Link to Jellyfin](https://jellyfin.org/)
- **Plex**: [Link to Plex](https://www.plex.tv/)
- **Sonarr**: [Link to Sonarr](https://sonarr.tv/)
- **Radarr**: [Link to Radarr](https://radarr.video/)
- **Synology Cloud**: [Link to Synology Cloud](https://www.synology.com/en-global/dsm/packages/Synology_Cloud)

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
