---
content_title: Uninstall Stinger
---

If you have previously built Stinger from source and now wish to install the prebuilt binaries, or to build from source again, it is recommended to run the `eosio_uninstall.sh` script within the `eos/scripts` folder:

```sh
cd ~/eosio/eos
sudo ./scripts/eosio_uninstall.sh
```

[[info | Uninstall Dependencies]]
| The uninstall script will also prompt the user to uninstall Stinger dependencies. This is recommended if installing prebuilt Stinger binaries or building Stinger for the first time.
