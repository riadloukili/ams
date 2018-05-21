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

*Note 2: You'll need to set up A records in your domain provider pointing to your server's ip*

# Usage

It's pretty straightforward

| Command       | Role                                                  |
|     :---:     |                      :---                             |
|    install    | Installs all the dependencies and sets up the server  |
|     start     | Starts all services and server                        |
|     stop      | Stops all services and server                         |
|    restart    | Does a stop then a start                              |

# Configure

A full tutorial can be found [here](https://github.com/riadloukili/ams/wiki/Installation-Guide).

# Contribution

All contributions are welcome, just make a pull request :)

# License

MIT License

Copyright (c) 2018 Riad Loukili

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
