# Code Club Scratch Curriculum

This repository contains all the material for Term 1 and 2 of [Code Club][codeclub].
It consists of lesson notes and plans in [Markdown][markdown] format,
[Scratch][scratch] project files, and a few PDFs.

This material is openly available for everyone to use and contribute to.
Right now, we’re receiving translations from all over the world.
See 'contributing' below to find out how you can take part.

## Notes on this Version

Just wanted to develop a more concise version; found that lessons involve sometimes tedious, confusing details that could be trimmed down. Also wanted to get rid of sound entirely; kids importing sounds turns into an unmanageable racket and the temptation to play the sounds over and over is too great.

## Contributing

To contribute:

1. Fork the repo
2. Add your new translation in its own folder *or*
   Add to one of the existing translations
3. Send us a pull request
4. Ask another native speaker to read through and comment with :+1:
   if they like your work

See [CONTRIBUTING.md](CONTRIBUTING.md) for more details.
## Discuss
Ask questions and share your experiences with other Code Clube World local teams in our community:
https://plus.google.com/communities/107429287353708601653

## Generating the language packs

Install dependencies

```shell
$ gem install rake rubyzip
```

Build the packs to pkg/

```shell
$ rake build
```

Or if you want to use bundler

```shell
$ bundle install
$ bundle exec rake build
```

## License

See [LICENSE.md](LICENSE.md)

## Warning

This repository uses Unicode filenames, which can break under OSX. You will need a version of Git above 1.8.2 and run `git config --global core.precomposeunicode true` before checking out the repository.

[codeclub]: http://codeclubworld.org/
[markdown]: http://daringfireball.net/projects/markdown/
[scratch]: http://scratch.mit.edu/

