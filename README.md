# flumble

Run a [Mumble](https://www.mumble.info/) server on [Fly.io](https://fly.io/).

## Usage

```bash
$ fly apps create my-awesome-mumble
$ fly secrets set MUMBLE_SUPERUSER_PASSWORD="secure_password"
$ fly secrets set MUMBLE_CONFIG_SERVER_PASSWORD="another_secure_password"
$ fly volumes create mumble --region fra --size 1 --app my-awesome-mumble
$ fly deploy --remote-only --config fly.toml
```

## License

```
Copyright 2022 Martin Simon

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

```

## Buy me a coffee?

If you feel like buying me a coffee (or a beer?), donations are welcome:

```
BTC : bc1qq04jnuqqavpccfptmddqjkg7cuspy3new4sxq9
DOGE: DRBkryyau5CMxpBzVmrBAjK6dVdMZSBsuS
ETH : 0x2238A11856428b72E80D70Be8666729497059d95
LTC : MQwXsBrArLRHQzwQZAjJPNrxGS1uNDDKX6
```
