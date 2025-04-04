# README

## About the Project

Heavily inspired by [this README template](https://github.com/othneildrew/Best-README-Template/blob/main/README.md),
this is a more minimal README template that only uses markdown. This template
is minimal and general-purpose enough that it should be relevant to most projects.
If there are any suggestions or modifications, feel free to contribute, fork
this repository, or use this as inspiration for your own READMEs!

### Built With

This section should list any major dependencies or libraries used in your
project. See below for an example of what a full-stack application's major
dependencies might look like.

- [![Svelte][svelte-shield]][svelte-url]
- [![Go][go-shield]][go-url]
- [![Gin][gin-shield]][gin-url]
- [![DuckDB][duckdb-shield]][duckdb-url]

## Getting Started

Here is where you should list any instructions on what others need to do in
order to set up this project. For example:

To get a local copy up and running, follow these steps.

### Prerequisites

This section is to show what is required to use the software and how to install
them or a link to installation. For example:

- [Python 3.11 or greater](https://www.python.org/downloads/)
- [uv](https://docs.astral.sh/uv/)
- DuckDB

```sh
curl https://install.duckdb.org | sh
```

### Installation

Here should be where the instructions on how to install the software lies. For example:

1. Clone the repo

```sh
git clone https://github.com/username/repo_name
```

2. Provide your environment variables in a `.env` file

```sh
KEY="YOUR_API_KEY_HERE"
```

3. Run the installation file

```sh
uv run install.py
```

### Usage

This section is where you should tell the user how the project can be used. Feel
free to add screenshots, code examples, or demos. If your repository has any
documentation hosted or included, link that here as well. For example:

To create a new foo, Instantiate a `Foo` class and pass in your foo values:

```py
foo: Foo = Foo("bar")
```

You can also create a foo from a fizz value:

```py
foo: Foo = Foo.from_fizz("fizz")
```

For more code examples, please refer to the [Documentation](https://www.example.com)

### Notes

You should include any additional notes regarding usage, deployment,
installation, etc. here. For example:

If you want to point to a remote database instead of a local DuckDB database,
set a `DB_PATH` environment variable:

```sh
DB_PATH="PATH_TO_DATABASE"
```

Doing this is not yet officially supported. Databases like MSSQL and MySQL might
not work as expected.

## Roadmap

This section should be a simple list of major feature plans. You can also link
to some dedicated document or resource for features. For example:

- [x] Add support for controllers
- [ ] Spanish translation
- [ ] Major weapon rebalance

See the [open issues](www.example.com) for a full list of proposed features. See
also [our Kanban board](www.example.com) for our officially accepted feature
list.

## Contributing

Contributions are what make the open source community such an amazing place to
learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and
create a pull request. You can also simply open an issue with the tag
"enhancement". Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (git checkout -b feature/AmazingFeature)
3. Commit your Changes (git commit -m 'Add some AmazingFeature')
4. Push to the Branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

## Contact

Here is where you should list your contact information, whether that be your
github account, email, social media, etc. It's up to you. Be sure to only list
platforms or methods of contact that you are comfortable with others using. Feel
free to link back to the project here as well. For example:

@seanpden - [BlueSky](https://bsky.app/profile/seanpden.bsky.social) - [email]

## Acknowledgments

This section is dedicated to any acknowledgments that would be appropriate. Some
examples would be projects you took inspiration from, assistance from
individuals, or helpful resources. This project's acknowledgments are as follows:

- Inspired by [this readme template](https://github.com/othneildrew/Best-README-Template/blob/main/README.md)
- [Static badge](https://shields.io/badges) used for the "Built With" badges

<!-- URL and Shields stored here -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[svelte-url]: https://svelte.dev/
[svelte-shield]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00

[go-shield]: https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=fff
[go-url]: https://go.dev/

[gin-shield]: https://img.shields.io/badge/Gin-f4f4f4?style=for-the-badge&logo=gin&logoColor=008ECF
[gin-url]: https://gin-gonic.com/

[duckdb-shield]: https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=000
[duckdb-url]: https://duckdb.org/
