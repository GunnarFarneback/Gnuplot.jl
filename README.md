# Gnuplot.jl
## A Julia interface to Gnuplot.

Build status  | [![Build Status](https://travis-ci.org/gcalderone/Gnuplot.jl.svg?branch=master)](https://travis-ci.org/gcalderone/Gnuplot.jl)
|  ---------- | -----------|
**License**        | [![License](http://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat)](LICENSE.md)
**Documentation**  | [![DocumentationStatus](https://img.shields.io/badge/docs-latest-blue.svg?style=flat)](https://gcalderone.github.io/Gnuplot.jl/dev/)
**Examples**       | ![Examples](https://img.shields.io/website?up_message=examples&url=https%3A%2F%2Flazarusa.github.io%2Fgnuplot-examples%2F)


**Gnuplot.jl** is a simple package able to send both data and commands from Julia to an underlying [gnuplot](http://gnuplot.sourceforge.net/) process.  Its main purpose it to provide a fast and powerful data visualization framework, using an extremely concise Julia syntax.


## Installation

Install with:
```julia
]dev Gnuplot
```
A working [gnuplot](http://gnuplot.sourceforge.net/) package must be installed on your platform.


Test package:
```julia
using Gnuplot
println(Gnuplot.gpversion())
test_terminal()
```


