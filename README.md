# Original Author
This was originally forked on this GitHub repo: [https://github.com/RubenVermeulen/generate-trusted-ssl-certificate](https://github.com/RubenVermeulen/generate-trusted-ssl-certificate)

## No license from original
The original author did not provide a license for this work.

Based on what this does, I added the GNU AGPL3 license for everyone to use.

## Disclaimer ⚠️
Should the original author wish for me to remove this, please contact me on [github@newteq.co.za](mailto:github@newteq.co.za)

# Generate a Trusted SSL Certificate

This repository contains a script that will generate a trusted ssl certificate which can be used for local software development.

```
git clone https://github.com/RubenVermeulen/generate-trusted-ssl-certificate.git
cd <PATH_TO_REPO_FOLDER>/generate-trusted-ssl-certificate
bash generate.sh
```

## Configuration

You can adjust the `[dn]` part of the `openssl-custom.cnf` file to whatever you prefer.

```
[dn]
C = <COUNTRY>
ST = <STATE>
L = <LOCALITY / CITY>
O = <ORGANIZATION>
OU = <ORGANIZATION_UNIT>
emailAddress = <EMAIL_ADDRESS>
CN = <HOSTNAME / IP_ADDRESS>
``` 
