# BBGD harmonization

Polish Household Budget Survey (Badanie budzetow gospodarstw domowych, BBGD) is published by Statistics Poland (GUS) since 1992. This code is used for harmonization of the changing structure of this survey. 

## How it works?
file _Wybór zmiennych_ contains a dictionary of harmonized variables

Notebook _BBGD Data preparation_ contains:
1. tools for analysis of the raw data in a search for inconsistencies in the original coding
2. a decoder that uses a dictionary of harmonized variables and applies it to raw data

## Additional notes.
1. raw data should be provided in csv format
2. when adding the new keys to harmonized dictionary follow strictly the existing format
