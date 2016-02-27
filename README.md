# mbed-autowriter

When you download mbed hex,bin files in downloads dir, autowrite to mbed mount volume.

## Installation

    $ gem install mbed-autowriter

## Usage

```
$ mbed-autowriter
$ mbed-autowriter -d /path/your_downloads_dir/ # set download dir
$ mbed-autowriter -m /Volumes/NODE_L476RG/ # set mbed mount volume
```

If you want auto umount, add sudo.

```
$ sudo mbed-autowriter
```

## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

