# DAppnodePackage-nextcloud

[![DAppNodeStore Available](https://img.shields.io/badge/DAppNodeStore-Available-brightgreen.svg)](http://my.admin.dnp.dappnode.eth/#/installer/nextcloud.public.dappnode.eth)

This package deploys a nextcloud instance in your DAppNode. To keep the package optimal and self-contained, only SQlite database backend is available.

Check [Nextcloud](https://nextcloud.com/) for more information.

## Building

`docker-compose build`

## Running

### Start

`docker-compose up -d`

### View logs

`docker-compose logs -f`

### Stop

`docker-compose down`

### License

This package maintains the AGPLv3 license of Nextcloud.