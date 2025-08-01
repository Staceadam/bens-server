## Setup
1. run the docker-compose.yml first without the additional vpn layer
2. once services are running and healthy, go to prowlarr (localhost:9696). go to step "3. Install and Set up Prowlarr through .exe files – Complete Walkthrough", [prowlarr guide](https://www.rapidseedbox.com/blog/prowlarr-guide#08), the .exe part is irrelevant and can be skipped. you need to configure:
- indexer (this is what searches for available files)
- a download client (qbittorent)
- Radarr (movie manager)
- Sonarr (tv manager)
3. Plex, Radarr, Sonarr and Overseerr are going to need additional configuration. there should be a setup wizard for each but the main thing is setting the media location for Plex, Radarr and Sonarr. 


## Gotchas
- you'll probably need to create the services/... directories for each service and might need to open up their permissions to 777 or whatever the service is expecting