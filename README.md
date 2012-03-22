# Homebrew-Liquidsoap

Cloned repository to support latest [Homebrew][homebrew] TAP function out of the box

## Requirements

* [Homebrew][homebrew]
* [Snow Leopard or Lion][apple] - Untested against Mountain Lion (Unknown)
* [Intel x86 and x64 processor][intel] (does not compile on [PowerPC][ppc] or [other old mac's][oldmacs])

## Installation

### Quick Start

brew tap drfill/liquidsoap

### Installing homebrew-liquidsoap Formulae

brew install liquidsoap

### Options available in liquidsoap

	--with-samplerate
		Enables Samplerate library support

	--with-xmlplaylist
		Enables XmlPlaylist support

	--with-lastfm
		Enables LAST.fm support

	--with-soundtouch
		Enables Soundtouch library support

	--with-aac
		Enables AAC library support

	--with-aacplus
		Enables AAC+ library support

## Usage

liquidsoap --help

## Todo

* TODO

## Bugs and other caveats

1. Lame library compiled in only if CPU x64
2. Soundtouch library compiled in only if CPU x86

## License

			GNU GENERAL PUBLIC LICENSE
				Version 2, June 1991
			
	Copyright (C) 1989, 1991 Free Software Foundation, Inc.
	59 Temple Place, Suite 330, Boston, MA  02111-1307  USA
	Everyone is permitted to copy and distribute verbatim copies
	of this license document, but changing it is not allowed.

full on http://savonet.hg.sourceforge.net/hgweb/savonet/savonet/raw-file/6e8a95e78fba/LICENSE


[homebrew]:https://github.com/mxcl/homebrew/wiki/installation
[apple]:http://apple.com
[intel]:http://intel.com
[ppc]:https://www-01.ibm.com/chips/techlib/techlib.nsf/products/PowerPC
[oldmacs]:http://myoldmac.net/cgi-data/gal/index.php