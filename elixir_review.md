Creating a elixir phoenix projects use:
mix <project_name>

Elixir methodis impicit return.

To try interactive SHOULD USE THIS to make project accesible:
iex -S mix

To reload interactive:
recompile

If the method returns a boolean add ? after the name of the method.


Enum module ussually like an array

Tuple in Elixir is {}

Elixir we can use tuple for return value

Tradional way of getting the index of an array or tuple is not effective in elixir.
Pattern Matching is elixir replacement for variable assignment.

After elixir is the erlang

:testing //this is an atom

pattern matching in variable, the string should match on the right:
["red", color] = ["red", "blue"]

To install a dependency use:
`mix deps.get`

To run test use: `mix test`


## maps
Map in elixir is the same with Python Dictionary, with keys and value. or same with Ruby
colors = %{primary: "red", secondary: "blue"}
# to access this use .:
colors.primary

Or by pattern Matching
# or using pattern matching:
%{secondary: secondary_color} = colors
https://hexdocs.pm/elixir/main/Map.html

Update using pipe:
%{colors | primary: "blue"}

## keyword list
colors = [{:primary, "red"}, {:secondary, "blue"}]
colors[:primary]