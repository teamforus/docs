# Contributing

I you want to contribute to the docs, read the [contribution manual](contribution-manual/README.md), and the [markdown styleguide.](markdown-styleguide/README.md)

If you want to work on the docs, it is highly recommended to test locally. It takes only a couple minutes to set up and helps you get faster feedback on how your changes will look on the website.

 ## How to run docs locally:

 This is a quick guide on how to run the docs site locally

 - install ruby (version 2.5 or higher recommended, if using any version prior to 2.5 you will need to install bundler with `gem install bundler`).
 - This step is for only macOS users:
     - You will need to have either `xcode` or the `xcode command line tools` installed. To install the command tools use `xcode-select --install`. Don't forget to accept the `sudo xcodebuild -license` command.
     - Depending on your setup you might need to install [nokogiri](http://www.nokogiri.org/tutorials/installing_nokogiri.html) and its dependencies manually.
 - Fork the [repository](https://github.com/teamforus/docs).
 - Clone your fork.
 - Run `bundle install` inside of the cloned docs folder.
 - Start the server with `bundle exec "jekyll serve --incremental --safe"`.
