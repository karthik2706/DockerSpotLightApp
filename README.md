Spotlight App running on Raspberry Pi
=======

[Building a SpoltLight app to work with Node.js and MongoDB]

## Installation

On the Raspberry Pi, install `docker-compose` version 1.1.0 with

```bash
curl -L https://github.com/hypriot/compose/releases/download/1.1.0-raspbian/docker-compose-`uname -s`-`uname -m` > /usr/local/bin/docker-compose
chmod +x /usr/local/bin/docker-compose
```

Now clone this repo and power up the two containers with `docker-compose up`.

```bash
git clone https://github.com/karthik2706/DockerSpotLightApp.git
cd DockerSpotLightApp
docker-compose build
docker-compose up
```

Now open a browser with

```bash
open http://ip-or-your-rpi:2000
open http://ip-or-your-rpi:2000/#developer
open http://ip-or-your-rpi:2000/#lead
open http://ip-or-your-rpi:2000/#manager
```
You can see the different behavior of logins with the above sample urls

Architecture
------------

![alt tag](https://raw.githubusercontent.com/karthik2706/DockerSpotLightApp/master/architecture.png)

License
-------

The MIT License (MIT)

Copyright (c) 2015 Karthik Dintakurthi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

