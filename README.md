This is the source for
[http://charlietanksley.github.io/latex-for-philosophers/index](http://charlietanksley.github.io/latex-for-philosophers/index).
The body of the site is in markdown files in the `source` directory.
The html files at the top level are generated via pandoc using a
simple build script.

## Stylesheets

I can't bear to write CSS straight. So I'm using Scss. And I'm using
Compass and Susy as framworks. If you need to do anything with the
stylesheets, you'll need to have a version of Ruby installed. Then
you'll need to

```shell
gem install bundler
bundle install
```

You can then run `compass watch` to compile your stylesheets on the
fly or `compass compile` to compile all your stylesheets at once.

## Contributing

1. Make a change to the appropriate markdown file.
2. Run `./build`.
3. Commit the change to the markdown and the change to the html.
4. Create a pull request.

