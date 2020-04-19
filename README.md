# Redgrid Pair Device

Using this script it is easy for anyone to pair a Genio device without having to use the phone app.

```
Pair a Genio device with the RedGrid TUYA cloud: index.js --ssid [string]
--password [string]

Options:
  --version   Show version number                                      [boolean]
  --ssid      The WiFi access point name (SSID) that the Genio device should
              connect to. This must be a 2.4GHz WiFi network (5GHz not
              supported)                                              [required]
  --password  The password for the WiFi access point.                 [required]
  -h, --help  Show help                                                [boolean]

```

## Simple Installation

If you want to simply run the script with minimal effort download the prebuilt version for your OS from the releases page.

## Development Installation

If you want to make some changes (or just don't want to install the 30MB binaries) you can get it up and running with the following

```bash
git clone https://github.com/redgridone/redgrid-pair-device
cd regrid-pair-device
npm install
node index.js --help
```