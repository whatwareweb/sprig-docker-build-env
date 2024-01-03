# sprig-docker-build-env
Docker image for Sprig/Spade development and builds

## Usage
 - Pull from docker: `docker pull whatware/sprig-build-env`
 - Run image with interactive terminal: `docker run -it whatware/sprig-build-env`
 - Go to spade repo directory: `cd ~/spade`
 - Run the spade minifier script: `./tools/jsdev.sh` and press Ctrl+C to exit because it doesn't exit by itself when finished
 - Follow the build instructions for your platform of choice on https://github.com/hackclub/spade

## Building
 - Clone this repo:
 - ```
   git clone https://github.com/whatwareweb/sprig-docker-build-env
   cd sprig-docker-build-env
   ```
 - Build with docker: `docker build .`


### Thank Yous
 - Hack Club Spade for making the thing in the first place https://github.com/hackclub/spade
 - Random person on Github for explaining the correct packages to install to cross compile for ARM https://github.com/johnwalicki/RaspPi-Pico-Examples-Fedora
