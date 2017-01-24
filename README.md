# PhoenixChatterbox

This is an experimental handler for [chatterbox](https://github.com/joedevivo/chatterbox).

## Installation

  1. Add `phoenix_chatterbox` to your list of dependencies in `mix.exs`:

    ```elixir
    def deps do
      [{:phoenix_chatterbox, github: "potatosalad/phoenix_chatterbox"}]
    end
    ```

  2. Ensure `phoenix_chatterbox` is started before your application:

    ```elixir
    def application do
      [applications: [:phoenix_chatterbox]]
    end
    ```

## Sample Application

### Phoenix

A sample application with plug is available at
https://github.com/potatosalad/phoenix_http2_example
