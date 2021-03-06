Handles flight tracks in [IGC](http://www.fai.org/component/phocadownload/category/?download=5745:igc-flight-recorder-specification-edition-2-with-al1-2011-5-31) format.

## Usage

    $ go get github.com/rochaporto/goigc

    $ ./goigc 
    $ Parse and analyse flight tracks in IGC format.
    $                          _______
    $                             |
    $ /--------------------------(_)--------------------------\
    $ 
    $ Usage:
    $   goigc [command]
    $ 
    $ Available Commands:
    $   convert     Convert track between different formats
    $   optimize    Optimize the track (for distance and score)
    $   show        Show track details
    $   version     Print version of goigc
    $ 
    $ Flags:
    $       --config="": config file (default is $HOME/.goigc.yaml)
    $   -h, --help[=false]: help for goigc
    $ 
    $ Use "goigc [command] --help" for more information about a command.

    $ goigc stats sample-flight.igc

    $ goigc optimize sample-flight.igc

## Documentation

    $ godoc github.com/rochaporto/goigc
