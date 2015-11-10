# repairMKV

Uses `mkvmerge` from [MKVToolNix](https://www.bunkus.org/videotools/mkvtoolnix/) to repair [MKV files](https://en.wikipedia.org/wiki/Matroska)

Originally authored by hd1080 over on the Plex forums - [source](https://forums.plex.tv/discussion/63691/how-to-automated-linux-script-for-fixing-broken-mkv-files-works-with-sickbeard-too)

Modified to work with "unfriendly" filenames and to pass [shellcheck](https://github.com/koalaman/shellcheck)

## Usage
    ./repairMKV.sh <file or folder> [options]

	Options:
	   -s Simulation mode, no files will be altered.
	   -f Forced mode, repair mkv anyway.
	   -h Show this help.
