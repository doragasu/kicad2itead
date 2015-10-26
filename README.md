# kicad2itead
Script to rename KiCad Gerber files to meet the naming convention required by iTead Studio. The scripts renames all the files it founds, and also adds them to a ZIP file, ready to be uploaded to iTead. Both the found and not found Gerber files are reported for the user to check everything goes as expected.

## Usage

    kicad2itead project_name

project name is the substring common to all generated Gerber file (usually the project name in KiCad).

## Note
This script works only for two layer PCBs, but could be easily extended for 4-layer boards (just add the corresponding fields to `ORG_FILES`, `DST_FILES` and `DESCRIPTS` variables).
