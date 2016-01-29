# Intro to Clojure and TDD

In this workshop we'll use the Clojure Koans exercises to start learning the basics of Clojure via a TDD-like feedback mechanism.

## Getting Started

Download the Koans project archive and unpack the zip file:
    $ wget https://github.com/functional-koans/clojure-koans/releases/download/0.5.0/clojure-koans-2014-10-09_08-31.zip
    $ mkdir clojure-koans
    $ cd clojure-koans/
    $ unzip ../clojure-koans-2014-10-09_08-31.zip



Next, open two terminal windows and run `./script/run` in one and `./script/repl` in the other.

The first command, `./script/run` will observe your koan exercises and automatically run them as their respective files are saved.

When the auto-runner finds an incomplete koan, it will print it and the file + line number where you can find it. Go ahead and open that file. The `__` is a placeholder for you to write a little bit of Clojure which completes the Koan.

The second command, `./script/repl` will launch an interactive console in which you can try out snippets of clojure. Try typing `(+ 1 1)` in the repl terminal and press enter.

## Resources

  * [Official Clojure Docs](https://clojuredocs.org/)
  * [Clojure Docs Quickref](https://clojuredocs.org/quickref)
  * [Mark Vokmann's Clojure Tutorial](http://java.ociweb.com/mark/clojure/article.html#Intro)
  * [Try Clojure (in-browser REPL tutorial)](http://www.tryclj.com/)
  * [Clojure Koans on Github](https://github.com/functional-koans/clojure-koans)
