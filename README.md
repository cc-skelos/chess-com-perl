# chess-com-perl
Example perl code to access JSON data from https://api.chess.com

This code is in the public domain.
Author: Giles Lean 2017.

# Basic Programs
These scripts are useful for basic connectivity testing and viewing
of unpacked JSON data from individual endpoints.
## lwp
Takes an endpoint as an argument and returns the JSON data
## lwp-debug
Similar to lwp, but will print some headers. Useful for debugging.
## lwp-dump
Similar to lwp, but will use Perl's JSON::PP and Data::Dumper to
display the JSON data as it has unpacked to perl hashes and arrays

# Example Programs
## clubs
Downloads a list of a player's clubs and sorts the human readable
names. Takes some seconds to run due to accessing each club's
endpoint as well as the player's club list.
## current-games
Download unfinished daily games in PGN format.


