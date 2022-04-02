# clay

[A big ball of mud](https://en.wikipedia.org/wiki/Big_ball_of_mud#In_relation_to_Lisp) with your favourite Clojure tools inside


Clay is a tiny Clojure tool for a dynamic workflow with the more serious visual tools

## Usage

Coming soon

## Development

Run the project's tests.

    $ clojure -T:build test

Run the project's CI pipeline and build a JAR.

    $ clojure -T:build ci

Install it locally (requires the `ci` task be run first):

    $ clojure -T:build install

Deploy it to Clojars -- needs `CLOJARS_USERNAME` and `CLOJARS_PASSWORD` environment
variables (requires the `ci` task be run first):

    $ clojure -T:build deploy

Your library will be deployed to org.scicloj/clay on clojars.org by default.

## License

Copyright © 2022 Scicloj

_EPLv1.0 is just the default for projects generated by `clj-new`: you are not_
_required to open source this project, nor are you required to use EPLv1.0!_
_Feel free to remove or change the `LICENSE` file and remove or update this_
_section of the `README.md` file!_

Distributed under the Eclipse Public License version 1.0.
