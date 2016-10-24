[![Build Status](https://travis-ci.org/tsoding/boids.svg?branch=master)](https://travis-ci.org/tsoding/boids)

# Boids in Haskell

http://www.red3d.com/cwr/boids/

## Usage

### NixOS

    $ nix-shell
    $ stack build --extra-include-dirs=$NIX_USER_PROFILE_DIR/include --extra-lib-dirs=$NIX_USER_PROFILE_DIR/lib
    $ stack exec boids-exe
    $ stack test
