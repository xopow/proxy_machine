<h1 align="center">Proxy Machine</h1>
<h2 align="center">
    <a href="https://github.com/batiscuff/proxy_machine/blob/main/LICENSE" target="_blank">
        <img alt="License: GPLv3" src="https://img.shields.io/badge/License-GPLv3-green.svg" />
    </a>
    <a href="https://github.com/psf/black" target="_blank">
        <img alt="Code style: black" src="https://img.shields.io/badge/code%20style-black-000000.svg" />
    </a>
    </a href="https://github.com/batiscuff/proxy_machine" target="_blank">
        <img alt="Build with love <3" src="https://img.shields.io/badge/build%20with-%F0%9F%92%9D-green" />
    </a>
</h2>

## Description
I did this project in order to boost views with the [teleboost :airplane:](https://github.com/crinny/teleboost/) in my Telegram channel. You can use it not only for boosting views but also for your own purposes. The maximum number of proxies you can get is 13.000 </br>
**List of sites for parsing proxies:**
- [free-proxy-list.net/anonymous-proxy.html](http://free-proxy-list.net/anonymous-proxy.html)
- [free-proxy-list.net](http://free-proxy-list.net)
- [proxy-daily.com](http://proxy-daily.com)
- [sslproxies.org](http://sslproxies.org)
- [free-proxy-list.net/uk-proxy.html](http://free-proxy-list.net/uk-proxy.html)
- [us-proxy.org](http://us-proxy.org)
- [api.proxyscrape.com](http://proxyscrape.com)
- [checkerproxy.net](http://checkerproxy.net)
- [proxy50-50.blogspot.com](http://proxy50-50.blogspot.com)
- [hidester.com](http://hidester.com)
- [awmproxy.net](http://awmproxy.net)
- [api.openproxy.space](http://openproxy.space)
- [aliveproxy.com](http://aliveproxy.com)
- [community.aliveproxy.com](http://community.aliveproxy.com)
- [hidemy.name](http://hidemy.name/en)
- [proxy11.com](http://proxy11.com)
- [spys.me](http://spys.me/proxy.txt)
- [proxysearcher](http://proxysearcher.sourceforge.net)
- [fatezero](http://static.fatezero.org/tmp/proxy.txt)
- [pubproxy](http://pubproxy.com/)
- [proxylists](http://www.proxylists.net/http_highanon.txt)
- [ab57ru](http://ab57.ru/downloads/proxylist.txt)
- [shifty-https](http://raw.githubusercontent.com/ShiftyTR/Proxy-List/master/https.txt)
- [shifty-http](http://raw.githubusercontent.com/ShiftyTR/Proxy-List/master/http.txt)
- [sunny9577](http://raw.githubusercontent.com/sunny9577/proxy-scraper/master/proxies.txt)
- [multiproxy](http://multiproxy.org/txt_all/proxy.txt)
- [rootjazz](http://rootjazz.com/proxies/proxies.txt)
- [proxyscan.io](http://www.proxyscan.io/api/proxy?format=txt&ping=500&limit=10000&type=http,https)

## Install 
```sh
sudo apt update && sudo apt upgrade
sudo apt-get install python3 python3-pip
git clone https://github.com/batiscuff/proxy_machine
cd proxy_machine
pip3 install -r requirements.txt
```

## Usage
```sh
python3 -m proxy_machine
```
#### Usage with proxy checker
```sh
python3 -m proxy_machine -pc
```
In this case, all parsed proxies will pass through the 
checker(this will take **2-4 hours**, prepare to wait) and
only working proxies will be written to *proxies.txt*.
#### Usage with other options
```sh
python3 -m proxy_machine -h
```

## License
**Copyright © 2021 [batiscuff](https://github.com/batiscuff)** <br />
**This project is GNU [General Public License v3.0](https://github.com/batiscuff/proxy_machine/blob/main/LICENSE) licensed**
