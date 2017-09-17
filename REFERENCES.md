# References/links to anything relevant to this project

### General
* [Elm Editor Support feature comparision](https://docs.google.com/spreadsheets/d/1JJ21llMKaIYzy449ILvyzQCCmoapJxbVGr-FyRUgKCw/edit#gid=0)

### Existing tool support in Elm
Official
* Elm-platform - https://github.com/elm-lang/elm-platform
* Elm-compiler - https://github.com/elm-lang/elm-compiler
* Elm-make - https://github.com/elm-lang/elm-make
* Elm-reactor - https://github.com/elm-lang/elm-reactor
* Elm-repl - https://github.com/elm-lang/elm-repl
* Elm-package - https://github.com/elm-lang/elm-package

Third-party
* Elm-oracle - https://github.com/ElmCast/elm-oracle
* Elm-format - https://github.com/avh4/elm-format
* Elm-analyse - https://github.com/stil4m/elm-analyse
* Json-to-elm - https://noredink.github.io/json-to-elm/
* Elm-version-manager - https://github.com/mattludwigs/elm-version-manager
* Create-elm-app - https://github.com/halfzebra/create-elm-app
* Elm-new - https://github.com/simonewebdesign/elm-new
* Elm-live - https://github.com/tomekwi/elm-live
* Elm-webpack-starter - https://github.com/elm-community/elm-webpack-starter
* Elm-search - http://klaftertief.github.io/elm-search/
* Ellie - https://ellie-app.com


### Alternatives and existing implementations/references
* [Haskell IDE Engine](https://github.com/haskell/haskell-ide-engine)
* [Rust Language server](https://github.com/rust-lang-nursery/rls)
* [Python Language server](https://github.com/palantir/python-language-server)
* [Other implementations - Language server protocol implementations and editor support](https://github.com/Microsoft/language-server-protocol/wiki/Protocol-Implementations)
* [Rust requirements document for the language server -with implementation discussion](https://github.com/rust-lang/rfcs/blob/master/text/1317-ide.md)

### Language Server Protocol
* The Language Server Protocol [(introduced in this blog post)](https://code.visualstudio.com/blogs/2016/06/27/common-language-protocol)
is used between a tool (the client) and the language server to integrate features used by the client. The protocol is based on  [JSON-RPC v2.0](http://www.jsonrpc.org/specification)
* [Main page for Language Server Protocol:](https://github.com/Microsoft/language-server-protocol)
* [Language Server Protocol/API](https://github.com/Microsoft/language-server-protocol)
* [Community site to track development process for LSP servers and clients](http://langserver.org/)
* [NB - new! GitHub and Facebook launches Atom-IDE (Atom Language Server Protocol support)](https://blog.atom.io/2017/09/12/announcing-atom-ide.html)

Language Server Protocol videos
* [Learning the Language Server protocol](https://www.youtube.com/watch?v=CJQqDdKl5TE)
* [Language Server Protocol - Why the hype?](https://www.youtube.com/watch?v=VfNQLjnS3QQ)
* [Language Server Protocol explained](https://www.youtube.com/watch?v=2GqpdfIAhz8)
* [Video - Magnus Rundberget - Elm Editor Support - Perspectives From an Editor Hacker | OsloElmDay 2017](https://www.youtube.com/watch?v=ExGkdmey0n4)

Language Server Protocol discussions
[Some IDE authors views on using language server/LSP for Rust] (https://www.reddit.com/r/rust/comments/6fs5q9/language_servers_and_ides/dinhtiz/)

### Discussions
* From Evan Czaplicki: elm-develop - [link](https://groups.google.com/d/msg/elm-dev/aDWFBg72Wt4/rF2h9-6nBAAJ)  What if it had special endpoints for editors?
* From Richard Feldman: - [link](https://groups.google.com/d/msg/elm-dev/aDWFBg72Wt4/5Lg_8p21BAAJ) A protocol editors could use to subscribe to information on builds that were kicked off by other tools.
* From Richard Feldman: - [link](https://groups.google.com/d/msg/elm-dev/aDWFBg72Wt4/mO3tTkW5BAAJ) Tell me all the dependencies.
* From Luke Westby - [link](https://groups.google.com/d/msg/elm-dev/aDWFBg72Wt4/0ZUKGOq7CQAJ) Information about a module that you might get today by manually parsing the .elmi file today
* From Magnus Rundberget -[link](https://groups.google.com/d/msg/elm-dev/uDGGTEh8ZYg/MNO19dYDAwAJ) Elm Tooling
