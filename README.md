```
   ▄████████ ███▄▄▄▄   ███    █▄    ▄▄▄▄███▄▄▄▄  
  ███    ███ ███▀▀▀██▄ ███    ███ ▄██▀▀▀███▀▀▀██▄
  ███    █▀  ███   ███ ███    ███ ███   ███   ███
 ▄███▄▄▄     ███   ███ ███    ███ ███   ███   ███
▀▀███▀▀▀     ███   ███ ███    ███ ███   ███   ███
  ███    █▄  ███   ███ ███    ███ ███   ███   ███
  ███    ███ ███   ███ ███    ███ ███   ███   ███
  ██████████  ▀█   █▀  ████████▀   ▀█   ███   █▀
```


# Enumeration script

## Requirements:

- Assetfinder : sudo apt install assetfinder

- owaspamass : https://owasp-amass.github.io/docs/

- httprobe : go install github.com/tomnomnom/httprobe@latest

- gowitness

## install

git clone https://github.com/MxSns/enumeration_script.git

chmod +x enumeration_script.sh

./enumeration_script.sh

## Features

- Creates directories for the results

- Potential takeovers:
Spots expired domain names that we can buy back if necessary.

It will use the subjack tool.

- Open ports:
It will scan open ports.

- Scraping wayback data:
It will use the waybackurls tool and pull all js, html, json, php, and aspx outputs, which sometimes contain stored credentials and keys that were previously there and may still work.

- Gowitness:
Finally, it will launch gowitness.
