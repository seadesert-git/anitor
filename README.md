<h1 align="center">AniTor</h1>
<p align="center">AniTor short for Anime Torrents is a tool to search and stream anime torrents from the terminal.</p>

### Working
The shell script scrapes for magnet links and uses [peerflix](https://github.com/mafintosh/peerflix) to stream anime.

## Preview
<img src="./preview.gif" alt="Preview" width="1280px">

## Usage
#### Searches for the anime based on query
`
$ anitor $SEARCH_QUERY
`
#### If query is not provided, then shows latest anime episode releases
`
$ anitor 
`
## Dependencies
* grep
* sed
* [peerflix](https://github.com/mafintosh/peerflix)

## Credits
The script uses NyaaFlix Unofficial API, [nyaasi-api](https://github.com/samedamci/nyaasi-api).

## Installation

```sh
$ sudo curl -o /usr/local/bin/anitor https://raw.githubusercontent.com/seadesert-git/anitor/master/anitor
$ sudo chmod +x /usr/local/bin/anitor
```

To uninstall,
`$ sudo rm /usr/local/bin/anitor`

## License
This project is licensed under [GPL-3.0](https://raw.githubusercontent.com/seadesert-git/anitor/master/LICENSE).
