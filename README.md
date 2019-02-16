# Bad Apple!! CLI

Bad Apple!! rendered in your terminal.

## Setup

First build the C application:

    make && cd src

You can run the C application standalone.

    ./badapple

To use the telnet server, you need to add a configuration that runs:

    badapple -t

We recommend `openbsd-inetd`, but both `xinetd` and `systemd` work as well. You
should be able to use any other compatible `inetd` flavor too.

## Licenses, References, etc.

The original source of the animation is
[prguitarman](http://www.prguitarman.com/index.php?id=348).

The code provided here is provided under the terms of the
[NCSA license](http://en.wikipedia.org/wiki/University_of_Illinois/NCSA_Open_Source_License).

More infomation:  
http://nyancat.dakko.us  
http://github.com/klange/nyancat
