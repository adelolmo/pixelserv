# pixelserv
Lightweight web server that serves a 1x1 transparent GIF.

Base on:
http://proxytunnel.sourceforge.net/files/pixelserv.pl.txt

## Install

```
wget https://github.com/adelolmo/pixelserv/releases/download/v1.0.0/pixelserv_1.0.0_all.deb
sudo dpkg -i pixelserv_1.0.0_all.deb
```
## Usage

To start the service:
```
sudo service pixelserv start
```

To stop the service:
```
sudo service pixelserv stop
```

## Configuration

The configuration file is located in ```/etc/pixelserv/config.conf```.
This is how the configuration file looks like:

```
%CFG = (
    'host' => '0.0.0.0',
    'port' => 80
);
```

```host``` is the hostname and ```port``` is the port where the webserver listens to.
