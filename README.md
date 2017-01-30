# Identicon

Given a username, create an identicon image representation (PNG format).

## Usage
```sh
$ iex -S mix
```

```elixir
Identicon.main("name here")
# -> :ok
```

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add identicon to your list of dependencies in `mix.exs`:

        def deps do
          [{:identicon, "~> 0.0.1"}]
        end

  2. Ensure identicon is started before your application:

        def application do
          [applications: [:identicon]]
        end
