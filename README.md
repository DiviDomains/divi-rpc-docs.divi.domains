# Divi RPC Documentation Generator

This tool extracts and formats the help text for each of the Divi RPC calls. The output of this script is hosted at [divi-rpc.github.io](https://divi-rpc.github.io). 

See the `script` directory for the `divi.go` script that generates the output and template.

### How to use

Ensure that you have Go installed and a working and running `divid` instance and that the `divi-cli` executable is available in `/usr/bin/divi-cli` (or update the path to your divi-cli executable in `divi.go`). From the `script` directory simply run `go run divi.go` and the documentation will be produced for all Divi RPC calls and styled according to the template in `template.html`.

## License

License of the docs is MIT (see https://github.com/DiviProject/Divi), license of the scripts and webpage is also MIT ((C) 2018 Karel Bilek, (C) 2022 Bert Shuler)
