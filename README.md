# clojure-playground

Learning some cool new stuff with clojure! 

This is my personal playground repository. I'll add code and documentation here while I follow the book [Clojure for the Brave and True](http://www.braveclojure.com/).

## Installation

Download from ...nowhere yet.

## Using Leiningen

This app has been generated with the following command:

`lein new app app-name`


Let's use [Leiningen](https://leiningen.org/) to run this thing...

- `lein run` Run it!
- `lein uberjar` Build a jar file
- `java -jar target/uberjar/clojure-noob-0.1.0-SNAPSHOT-standalone.jar` Run the generated jar file

Other commands:

- `lein eastwood` run the linter
- `lein cloverage` analyze the test coverage
- `lein ancient` search for outdated dependencies
- `lein kibit` analyze the code and suggest more idiomatic variants

Using the REPL:

- `lein repl` Start it!

## While using EMACS

Run the function `M-x cider-jack-in RET` to start the REPL in a new window.

Select code and press `C-x C-e` in order to send it for evaluation into the REPL.

While working on a `.clj` file/buffer, use `C-c M-n` to set the namespace to the one specified on the top of the file.

After editing a `.clj` file, use `C-c C-k` to compile it within the REPL session.

## About Clojure

## License

Copyright © 2017

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
