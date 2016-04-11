# ILikeThisThing
> This is a thing. And I like it! [https://ilikethis.herokuapp.com/](https://ilikethis.herokuapp.com/)

## Team
- **Product Owner**: Natalie
- **Scrum Master**: Justin
- **Development Team Members**: Brad, Julia

## Table of Contents
1. [Usage](#Usage)
2. [Requirements](#requirements)
3. [Development](#development)
  1. [Installing Dependencies](#installing-dependencies)
  2. [Tasks](#tasks)

4. [Team](#team)
5. [Contributing](#contributing)

## Usage
> Some usage instructions

## Requirements
- Node 5.5.0
- Postgresql 9.5.x
- Express ^4.13.4

## Development
### Installing Dependencies
From within the root directory:

```sh
npm install
```

- npm install will run bower install after npm completes

To install Postgresql and start up local db server:

```sh
brew install postgresql
postgres -D /usr/local/var/postgres
createdb ilikethis_dev
```

See this [blog post](http://www.dancorman.com/knex-your-sql-best-friend/) for more information on setting up postgresql. If the database needs to be dropped run dropdb ilikethis_dev and then recreate

You will need an API key for GiantBomb (game api).

Google Books and OMBD (IMDB's api) are the other two apis and do not require apiKeys
