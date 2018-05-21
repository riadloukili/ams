# Auto Media Server
A media server using Traefik with Plex, Sonarr, Radarr, Deluge and Portainer

# Installation
This script has only been tested in Ubuntu 16.04. Though it's not guaranteed, it may work on other dist as well.

To install run:
```shell
cd ~
curl -s https://raw.githubusercontent.com/riadloukili/ams/master/ams > ams
chmod +x ams
./ams install
```

*Note: This script has only been tested as **root**...*

# Usage
It's pretty straightforward

| Command       | Role                                                  |
|     :---:     |                      :---                             |
|    install    | Installs all the dependencies and sets up the server  |
|     start     | Starts all services and server                        |
|     stop      | Stops all services and server                         |
|    restart    | Does a stop then a start                              |
