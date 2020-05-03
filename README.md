# shairport-sync-snap
Snapcraft files for shairport-sync an AirPlay daemon


# Building

To build this snap by your own clone this repository and run snapcraft in the top of this source tree

```
sudo snap install snapcraft --classic
git clone https://github.com/TeamRocketBox/shairport-sync-snap.git
cd shairport-sync-snap
snapcraft
````

## Installing the dev package

After you have successfully build the development package this can be installed like this

```
sudo snap install shairport-sync_3.3.5_amd64.snap --devmode
```
