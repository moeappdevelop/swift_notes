1.sudo apt-get install clang libicu-dev
```
sudo apt-get install clang libicu-dev
sudo apt-get install clang
```
2.Download the latest binary release

3.设置gpg

https://swift.org/download/#using-downloads

```
wget -q -O - https://swift.org/keys/all-keys.asc | gpg --import -

$ gpg --keyserver hkp://pool.sks-keyservers.net --refresh-keys Swift

$ gpg --verify swift-<VERSION>-<PLATFORM>.tar.gz.sig

tar xzf swift-<VERSION>-<PLATFORM>.tar.gz

export PATH=/path/to/usr/bin:"${PATH}"
```