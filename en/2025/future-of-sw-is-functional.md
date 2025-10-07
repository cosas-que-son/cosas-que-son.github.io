*[Home](../../README.md)*

# The future of software development is functional

*April 30, 2025*

There is a saying that Lisp programmers — since the 1950s! — just sit back and
watch how other programming languages slowly implement functional programming
features which were available to Lispers right from the start. The following
examples show that this is true and that the functional paradigm is influencing
more than just programming languages.

## Case 1: Lambdas
Lambdas are anonymous functions which can be created at runtime, passed as
parameters and returned by other functions. Functional programmers use them all
the time in the same natural way as they use integers or strings. This used to
sound quite esoteric to OO programmers until lambdas were finally introduced in
C++ and — after heated discussions — even in Java.

## Case 2: React
One of the most popular libraries for web development,
[React](https://react.dev/), embraced functional programming principles (like
encouraging immutable state) from the start. It is even more interesting that
functional components (“hooks”) replaced class components ([which now are just
“supported”](https://react.dev/blog/2023/03/16/introducing-react-dev#going-all-in-on-modern-react-with-hooks)).
According to [Wikipedia](https://en.wikipedia.org/wiki/React_(software)):

> *The introduction of React Hooks with React 16.8 in February 2019 allowed
> developers to manage state and lifecycle behaviors within functional
> components, reducing the reliance on class components.*

> *This trend aligns with the broader industry movement towards functional
> programming and modular design.*

## Case 3: Bazel
[Bazel](https://bazel.build/) is an ambitious open-source build and test
software system created by Google which aims for speed, correctness and
reproducibility. [The underlying
model](https://bazel.build/basics/artifact-based-builds) sees a build process
as transforming input files to binaries:

> *The easiest problems to express using functional programming are the ones
> that simply involve transforming one piece of data into another using a
> series of rules or functions. And that’s exactly what a build system is: the
> whole system is effectively a mathematical function that takes source files
> (and tools like the compiler) as inputs and produces binaries as outputs. So,
> it’s not surprising that it works well to base a build system around the
> tenets of functional programming.*

## Case 4: Unit testing
Unit tests only make sense if they use as little mocking as possible —
otherwise you end up testing mocks instead of the actual source code. The best
way to achieve this is writing functions or methods that have as little state
as possible and depend only on their parameter lists. In other words: write the
methods in your OO language in a “function-oriented” way.

----

## Conclusion

The examples above show that the software development world is becoming
functional — it is therefore a smart move to add a functional programming
language to your toolbox. Here are some of the languages you may choose from:

* [Haskell](https://www.haskell.org/) is a purely functional language — you get
  the full benefits but it has reportedly a steep learning curve.
* [Clojure](https://clojure.org/) is a pragmatic Lisp dialect which is fully
  integrated in the Java ecosystem. Using
  [ClojureScript](https://clojurescript.org/), it is possible to write Clojure
  programs that run on the web browser.
* [Elixir](https://elixir-lang.org/) has excellent support for writing
  distributed and fault-tolerant programs for the robust Erlang VM.
* [Scheme](https://www.scheme.org/) is the Lisp dialect used in the classic
  [*Structure and Interpretation of Computer
  Programs*](https://xuanji.appspot.com/isicp/) textbook.
* [F#](https://fsharp.org/) is Microsoft’s functional language for .NET and one
  strong sign that functional programming is going mainstream.
