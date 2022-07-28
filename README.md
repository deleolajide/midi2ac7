# midi2ac7
Utility to create a Casio AC7 style/rhythm file from MIDI files of each music section.

It uses [ac7maker](https://github.com/michgz/ac7maker) to create the casio ac7 file.

I use it create Casio AC7 style files for my portable CT-S500 keyboard from my Ketron SD90 arranger. I follow the following procedure :

- The Ketron style is exported using Style export feature and the generated folders are copied to my PC via a USB drive.
- The generated midi files are then converted from type 0 to type 1
- I create a JSON file for ac7maker from a suitable template
- Run the build.cmd script to create the AC7 file
- Copy the AC7 style file from my PC to the CT-S500 via a USB drive

See the [havent_found](https://github.com/deleolajide/midi2ac7/tree/main/havent_found) folder for an example.
