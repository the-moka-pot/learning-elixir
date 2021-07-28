# learning-elixir
A collection of LiveBook notebooks to introduce Elixir and Data Manipulation on Elixir

## Usage

You will need Elixir v1.12 or later. Livebook also requires the following Erlang applications: `inets`, `os_mon`, `runtime_tools`, and `ssl`. Those applications come with most Erlang distributions but certain package managers may split them apart. For example, on Ubuntu, these Erlang applications could be installed as follows:

```sudo apt install erlang-inets erlang-os-mon erlang-runtime-tools erlang-ssl```
Running Livebook using Escript makes for a very convenient option for local usage and provides easy configuration via CLI options.

```mix escript.install hex livebook```

### Start the Livebook server
```livebook server```

### See all the configuration options
```livebook server --help```
After you install the escript, make sure you add the directory where Elixir keeps escripts to your `$PATH`. If you installed Elixir with `asdf`, you'll need to run `asdf reshim elixir` once the escript is built.