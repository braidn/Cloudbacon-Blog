---
title: Problem Solving In Golang
date: '2015-03-20'
---

Nope, not actually problem solving because that is in fact boring, something that no one is really interested in and somewhat of a non starter. Doubley so when things haven't been updated much around here. Go or GoLang is a fantastic language at hunting down problems, or what some would call "debugging". I would call it debugging as well however, I am sure there are a myriad of words that all mean the same thing.

Whenever a Go program comes under the green light, the developer uses the handy `run` command. This kicks off the compile step inheret in Go programming; and, since this is in fact programming, there will be errors.  These errors are accompanied by a somewhat small stacktrace (thank you Rob) along with the line number where the offense is occurring. The greatest thing is that these exceptions are small, readable (by humans) and consise.  A programmer with little information on the language mechanics can read: "no method x exists for x" and realize they likely lower cased the first character of the method's name. Or perhaps they should just look back through through the documentation one more time to see where they took the incorrect turn.

ALSO! Captial methods... Good one.

Overall, a Luddite as myself can figure out what is going on in a language that I am actively learning and feel satisfied. No stacktraces where you have to increase the lines recorded in Tmux. Just a few lines... For humans.
