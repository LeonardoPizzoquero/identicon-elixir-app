# Identicon

Identicon generator app based on Github Avatar Generator created with Elixir.

## How to use

Run the command to start the Interactive mode of elixir: 

> iex -S mix

After that call the main method of the app passing a random string:
> Identicon.main("example")

By the end the program will generate a image file inside the folder with the random string.

## Example:

![Print](https://github.com/LeonardoPizzoquero/identicon-elixir-app/blob/main/example.png)

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `identicon` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:identicon, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/identicon](https://hexdocs.pm/identicon).

