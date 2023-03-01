# WikiCrawler

This is an Elixir web scrapper project that collects information from wikipedia about a specific subject and generates a mini compendium in pdf with this information

## Requirements

Before running this project, you need to have following tools installed on your computer:<br>
  - Elixir
  - Mix (Elixir package manager)

You'll also need to create a account on the Wikipedia API to obtain an access key and connect to the API.

## How to use

1. Clone this repository to your computer.

```bash
git clone https://github.com/your-username/wikipedia-scraper-elixir.git
```

2. Open a terminal in the project directory and install Elixir dependencies

```bash
mix deps.get
```

3. Open the `config/config.exs` file and insert your Wikipedia API access key

```elixir
config :wikipedia_scraper, api_key: "YOUR_ACCESS_KEY"
```

4. Run the project with the command below and replace the term `Subject` with the subject you want to collect information from on the Wikipedia.

```bash
mix wikicrawler "Subject"
```

5. The script will collect information from Wikipedia about the chosen subject and generate a mini compendium in PDF in the output folder.

## Contributing

If you'd like to contribute to this project, feel free to open an issue or submit a pull requests.

## License

This project is licensed under the MIT License. See the LICENSE file for more information.
