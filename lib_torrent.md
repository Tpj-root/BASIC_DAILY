# BASIC_DAILY


```

https://github.com/arvidn/libtorrent

```


Install the library system-wide

```
sudo cp libtorrent-rasterbar.so* /usr/local/lib/
sudo ldconfig

```


Keep it local (without installing)


```
export LD_LIBRARY_PATH=$HOME/Desktop/build/libtorrent/examples/build:$LD_LIBRARY_PATH
./simple_client 52ee22fc06aee53a7b2a1cb74ba97c8904f385f6.torrent


```


Or permanently add to ~/.bashrc

```
echo 'export LD_LIBRARY_PATH=$HOME/Desktop/build/libtorrent/examples/build:$LD_LIBRARY_PATH' >> ~/.bashrc
source ~/.bashrc

```


build_help

```
feature_option(build_tests "build tests" ON)
feature_option(build_examples "build examples" ON)
feature_option(build_tools "build tools" OFF)

```















In Debian with Transmission, torrent files can be stored anywhere you want, but usually they go in a dedicated folder. By default:

```

/home/where/.config/transmission/torrents/

/home/where/.config/transmission/torrents/b2e826ec7c5b11f63a2383d0d5da55d4432a0ddd.torrent

```