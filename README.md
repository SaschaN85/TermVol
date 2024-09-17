# TermVol

TermVol is a simple, terminal-based volume controller for Linux systems.

## Installation

1. Go to the [Releases](https://github.com/SaschaN85/TermVol/releases) page.
2. Download the latest `termvol_x.x.deb` file.
3. Install the package using:
	sudo dpkg -i termvol_x.x.deb

If you encounter any dependency issues, run:
	sudo apt-get install -f


## Usage

Open a terminal and type `termvol` to launch the application.

- Use left and right arrow keys to adjust volume.
- Use number keys 1-9 to set volume to 10%-90%.
- Press '0' to mute/unmute.
- Press 'q' to quit.

## License

This software is proprietary. See the LICENSE file for details.

## Dependencies

TermVol uses the Advanced Linux Sound Architecture (ALSA), which is licensed under the GNU Lesser General Public License (LGPL).
