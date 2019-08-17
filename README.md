Example config.json

{
  "bridge": {
    "name": "Homebridge",
    "username": "AA:BB:CC:DD:EE:FF",
    "port": 51826,
    "pin": "031-45-154"
  },
  "description": "This is an example configuration file with carwings plugin.",
  "accessories": [
    {
      "accessory": "Carwings",
      "name": "Leaf",
      "email": "example@youremail.com",
      "password": "TmljZVRyeSE=",
      "region": "NE",
      "updateInterval": "never"
    }
  ],
  "platforms": [
  ]
}
Region options: NNA = USA [default], NE = Europe, NCI = Canada, NMA = Australia, NML = Japan. (source)

