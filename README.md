# Dev'In Perigueux

## Contribution

Contribution in [Markdown](https://www.markdownguide.org).

* New posts in [_posts](/_posts/)
* New members in [_members](/_members/)
    * Illustrative images are taken from [Gravatars](https://gravatar.com). 

Deployement: Netlify, webhooked on the [`master`branch](https://github.com/dev-in-perigueux/dev-in-perigueux.fr/commits/master) accepted commits (feel free to propose a <abbr title="Pull Request">PR</abbr>).


## Development

### Dependencies

* [git](https://git-scm.com/)
* [bundler (ruby)](https://bundler.io/)

### Clone sources

```
git https://github.com/dev-in-perigueux/dev-in-perigueux.fr.git
cd dev-in-perigueux.fr
```

### Install Ruby deps

```
bundle install
```

### Development

```
bundle exec rake
```

### Build Wooster

```
bundle exec rake build:generate[prod]
```

### Test build

```
bundle exec rake test
```