# Dev'In Perigueux

## Dependencies

* [git](https://git-scm.com/)
* [bundler (ruby)](https://bundler.io/)

## Clone sources

```
git https://github.com/dev-in-perigueux/dev-in-perigueux.fr.git
cd dev-in-perigueux.fr
```

## Install Ruby deps

```
bundle install
```

## Development

```
bundle exec rake
```

## Build Wooster

```
bundle exec rake build:generate[prod]
```

## Test build

```
bundle exec rake test
```