# ClojureScript 30

This repo illustrates the projects I worked on which enabled me to go from an [early to beginner ](https://zedshaw.com/2015/06/16/early-vs-beginning-coders/) Clojure/ClojureScript (clj/cljs) developer.

Aside from teaching myself `clj/cljs`, I believe that `clj/cljs` is missing approachable documentation.  Maybe this repo can help round out some of the missing components for future learners.

In this spirit, my hope is that people find this repo a helpful learning tool.  My recommended approach to using this repo as a learning tool:

1.  Start with this repos [Getting Started](getting-started) guide
2.  Run through the first 3 [Modern CLJS](https://github.com/magomimmo/modern-cljs) tutorials
3.  Head over to [ClojureScript 30](https://javascript30.com/), try to complete each of the tutorials there.  When you get stuck, feel free to come over here to see how I did it and my annotations for why I did what I did.  But be sure to give EVERYTHING a try!
4.  If you came up with a question that you had as an early learner, that I did not have, or an issue you ran into that I did not, it would be amazing if we could compile them here.  This might help us gain insight into how we can better help new developers to join the Clojure community.


# Getting Started

Before you can start working on `clj/cljs` you need to setup your development environment.  This guide is **OSX** only.

## Install Java

see [clojure guide - install java](https://tkjone.github.io/clojure-guide/v1/guide/#Install-Java)

## Install Boot

see [clojure guide - install boot](https://tkjone.github.io/clojure-guide/v1/guide/#Install-Boot)

## Editor Setup

The most common suggestions for editors I have seen for Clojure/ClojureScript are [Emacs](https://www.gnu.org/software/emacs/), [vim](http://www.vim.org/) and [Intelij Cursive](https://cursive-ide.com/userguide/paredit.html).  However, I prefer to keep it simple and use [Atom](https://atom.io/).  I believe that this is likely the easiest introduction for new developers as there is huge community support, strong support for the `clj/cljs` language and you don't have to learn a myriad of hot keys.

> To emacs/vim people, this is not a slight against your editors.  These are amazing editors and people should learn them.  When I was learning clojure, I took the time to work with them and the burden on my original goal of learning clj/cljs was too great.

With this in mind, here are packages that I have added to my Atom setup to help working with Clojure an even more enjoyable experience:

* [language-clojure](https://atom.io/packages/language-clojure)
* [proto-repl](https://atom.io/packages/proto-repl)
* [proto-repl-charts](https://atom.io/packages/proto-repl-charts)
* [ink](https://atom.io/packages/ink)
* [parinfer](https://atom.io/packages/parinfer)


# Content Overview

Each sub directory in this repo reflects an individual project in the order in which I completed them.  Each will provide their own README where you can go to learn more about each one.

Each repo represents a stand alone project.  The first 3 projects are 100% [Modern CLJS](https://github.com/magomimmo/modern-cljs) and I recommend going to his first 3 tutorials to grasp them.  The rest are straight lessons from [JavaScript 30](https://javascript30.com/) of which I have heavily annotated for `cljs`.

* [00-setup]()
* 01-setup-reload
* 02-setup-reload-cleaner
* 03-drumkit

# Background

Please note that I am a developer by trade, so I went into this with a solid understanding of development patterns and languages and most importantly **how** to learn languages.

If you are to this, or any other language, do not let the above paragraph discourage you.  When I wrote this I was, still and likely never will be a programming prodigy.  What I do is grind it out and never stop myself from asking questions, no matter how foolish they may seem.

# Special Thanks

I want to thank [wes bos](https://github.com/wesbos) for providing an amazing course that I believe could be used to help developers learn not just JavaScript, but any language that compiles to JS.  For example:

  * Elm
  * ClojureScript
  * Dart
  * ElixirScript

and the above list goes on, but the ones I mentioned are the ones that are more interesting to me and likely more well known.

Big thanks also goes to [Modern CLJS](https://github.com/magomimmo/modern-cljs) and the whole of the [clj/cljs community](http://clojurians.net/) which is by far one of the friendliest, most willing and easily accesibly communities I have experienced.  Treat them with respect!
