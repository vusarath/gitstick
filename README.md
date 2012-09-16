# gitstick

gitstick is a distributed bug tracking tool integrated with git. It provides a web server, along with some command line utilities, for managing tickets.

Coming soon 

## Usage

Run gitstick in a new directory, or an existing git repository

    gitstick

Open `http://localhost:8080/` in a browser.
Enter credentials. In open mode, the password is not checked. A default user is created depending on your global or local git user configuration; the default password is the user name.

## Documentation

Visit the [wiki](http://darth10.github.com/gitstick) for more information.
To generate the API documentation, use `sbt doc`.

## Contributing

[Sbt](http://github.com/harrah/xsbt/wiki) is required for all development.

You can start a development server by using the `container:start` sbt command.
Run tests via the `test` command.

The project can be packaged into a war using `package-war`, or jar using `assembly`.

It's recommended that you use Eclipse or Emacs (with Ensime).
Use the `eclipse` or `ensime generate` sbt commands to generate project files for Eclipse and Emacs respectively.

## Credits

* [Ticgit-Ng](http://github.com/schacon/ticgit/wiki)
* [Scalatra](http://www.scalatra.org/)
* [JGit](http://www.eclipse.org/jgit/)

