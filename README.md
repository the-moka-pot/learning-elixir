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

## Data

#### Vaccindation Dataset

"COVID-19 in India" by @sudalairajkumar on Kaggle.
https://www.kaggle.com/sudalairajkumar/covid19-in-india?select=covid_vaccine_statewise.csv
(last updated from source on 28 Jul, 2021)

From this dataset the project uses, India's statewise COVID vaccination under `data/covid-vaccination/covid_vaccine_statewise.csv`.

#### Population Dataset

"COVID-19 Vaccination India : District wise data" by @arnabbiswas1 on Kaggle.
https://www.kaggle.com/arnabbiswas1/covid-vaccination-india-district-wise-data?select=india_state_wise_projected_population_2021.csv
(last updated from source on 28 Jul, 2021)

From this dataset the project uses, India's statewise Projected Population under `data/population/india_state_wise_projected_population_2021.csv`.
