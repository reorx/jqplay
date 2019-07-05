# jqplay

This is a fork of [jingweno/jqplay](https://github.com/jingweno/jqplay),
the aim is to improve the original project on the following aspects:

- [ ] Page layout
  - [ ] main page should not scroll, reduce space, increase density
  - [ ] move cheatsheet to foldable sidebar
- [ ] Backend storage
  - [ ] replace postgresql with embedded db
- [ ] Snippet
  - [ ] add name, author for snippet
  - [ ] add page to list and search snippets
- [ ] Ability to flat input json in (catj)[https://github.com/soheilpro/catj] output


## Development

To develop `jqplay`, you need to have a [Go development environment](http://golang.org/doc/install).
You also need to have Node & Postgresql installed.

### bin/setup

This script will setup Postgresql for `jqplay`.

### bin/start

This script will build and start the `jqplay` server.


## License

jqplay is released under the MIT license. See [LICENSE.md](https://github.com/jingweno/jqplay/blob/master/LICENSE.md).
