# youhou
[![Dependency Status](https://david-dm.org/neoziro/youhou.svg?theme=shields.io)](https://david-dm.org/neoziro/youhou)
[![devDependency Status](https://david-dm.org/neoziro/youhou/dev-status.svg?theme=shields.io)](https://david-dm.org/neoziro/youhou#info=devDependencies)

Easily broadcast your hostname in using Multicast DNS.

## Install

```
npm install -g youhou
```

## Usage

```
$ youhou 3000
Multicast DNS started for: http://Gregs-MacBook-Pro.local:3000
```

```
  Usage: youhou <port>

  Options:

    -h, --help              output usage information
    -V, --version           output the version number
    -p, --protocol [value]  Protocol. Default to "tcp".
    -t, --type [value]      Type. Default to "http".
    -n, --name [value]      Name. Default to "youhou".
```

## License

MIT
