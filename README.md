

#### UWU ~ `flatpak-builder` required from distro
```
flatpak install runtime/org.freedesktop.Sdk.Extension.openjdk8/$(uname -m)/22.08 \
                runtime/org.freedesktop.Sdk.Extension.openjdk17/$(uname -m)/22.08 \
                runtime/org.kde.Platform/$(uname -m)/5.15-22.08
```
```                
git clone --recursive https://github.com/saori-yuko/org.fn2006.PollyMC.git
```
```
cd org.fn2006.PollyMC
```
```
flatpak-builder build *.yml --user --force-clean --install
```
#### Enjoy! :)
https://github.com/fn2006/PollyMC
