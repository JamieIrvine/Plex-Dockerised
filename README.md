A docker-compose file to run Plex and PlexPy services.

# Setup
1. Set PLEX_UID and PLEX_GID to respective values for the user you want to run the services under.
2. Ammend data volume path to location of media files (May have some permission trouble accessing this folder if mounted under a different user than Plex is running under

# Running
docker-compose run -d 

## Web UIs
Plex: localhost:32400/web  
PlexPy: localhost:8181

# Stopping 
docker-compose stop

