# UTDF-CLI
[![Go Report Card](https://goreportcard.com/badge/github.com/attron/utdf-cli)](https://goreportcard.com/report/github.com/attron/utdf-cli)
CLI Tool For UTDF Spacecraft Packet Decoding and Processing

# USAGE
------------------------------------------------------------------
```bash
    ./utdf-cli 
        -filename string
            file that contains utdf data
        -output string
    	    save output of cli to file
        -run string
            run specific command (default "ToString")
```

# Building for development
------------------------------------------------------------------
```bash
    go build
```

Full list of commands can be found at the [utdfgo repo](https://github.com/ATTron/utdfgo/blob/master/README.md)