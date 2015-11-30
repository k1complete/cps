# Cps

A Continuation-passing style macro and non-deterministic operator for Elixir.


## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add cps to your list of dependencies in `mix.exs`:

        def deps do
          [{:cps, "~> 0.0.1"}]
        end
     or
        def deps do
          [{:cps, github: "k1complete/cps" }]
        end

  2. Ensure cps is started before your application:

        def application do
          [applications: [:cps]]
        end

