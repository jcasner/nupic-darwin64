# nupic-darwin64

Python distribution for NuPIC on OS X.  This project provides a
fully-functional python environment in which to build and run
[NuPIC](https://github.com/numenta/nupic) in a darwin64 (OS X) environment.

## Usage

Clone this repository:

    git clone https://github.com/numenta/nupic-darwin64.git

Activate your environment:

    source nupic-darwin64/bin/activate

Build NuPIC:

See https://github.com/numenta/nupic#configure-and-generate-build-files for
details.

To exit this environment when you are done:

    deactivate_nupic

To exit this environment when you are done: 

    deactivate_nupic

## Building nupic requirements

A Makefile is provided should you need to reconstruct this environment.

    source bin/activate
    make
