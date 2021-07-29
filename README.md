# Phoenix Snippets
This project was forked off of [jamilabreau's](https://github.com/jamilabreu/vscode-phoenix-snippets) snippets.  I wanted to use the snippets in vim w/ [vim-vsnip](https://github.com/hrsh7th/vim-vsnip), a Vim plugin that allows you to use visual studio code snippets.  It looks for snippets.json, so I'm splitting up the project into one for `.ex` and one for `.eex`.

## Snippets

Check out [the snippet files on Github](https://github.com/jamilabreu/vscode-phoenix-snippets/tree/master/snippets) for an up-to-date list of snippets.

### Shortcuts

|                                         To create...                                          | Use shortcut |
| :-------------------------------------------------------------------------------------------: | :----------: |
|                                        inspect(\_\_\_)                                        |      i       |
|                                      IO.inspect(\_\_\_)                                       |      io      |
|                             IO.inspect(\_\_\_, label: \"\_\_\_\")                             |     iol      |
|                                 defmodule \_\_\_Web.\_\_\_ do                                 |     plug     |
|                            defmodule \_\_\_Web.\_\_\_Controller do                            |      co      |
|                               defmodule \_\_\_Web.\_\_\_Live do                               |      lv      |
|                            defmodule \_\_\_Web.\_\_\_Component do                             |      lc      |
|                              defmodule \_\_\_Web.\_\_\_View do"                               |      vi      |
|                                           ~L\"\"\"                                            |      sl      |
|                                assign(socket, \_\_\_: \_\_\_)                                 |      a       |
|                        def handle_event(\"\_\_\_\", \_\_\_, socket) do                        |      he      |
|                            def handle_info(\"\_\_\_\", socket) do                             |      hi      |
|                          def handle_params(params, \_url, socket) do                          |      hp      |
|                              def render(assigns) do\n\t~L\"\"\"                               |      re      |
| def render(assigns) do\n\tPhoenix.View.render(\_\_\_Web.\_\_\_View, \"\_\_\_.html\", assigns) |     ret      |
