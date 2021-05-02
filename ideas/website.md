# Redesign and Polish Yao Website

*easy*

## Improve whole website banner

Documenter currently do not support custom banner, implement this feature request
based on previous hacks. ([Documenter/#1132](https://github.com/JuliaDocs/Documenter.jl/issues/1132)).

## Improve Tutorial CI pipeline

polish Pluto notebook layout on our tutorial website, replace the
`<iframe>` implementation with native `<div>`.

## Improve Documentation pipeline

1. move all documentation & website to one repo
2. implement CI to auto build documentation from component packages on tagged version and master/main branch

## Improve Website Style

1. improve CSS to have more consistent style.
2. improve large screen experience ([Documenter/#1563](https://github.com/JuliaDocs/Documenter.jl/issues/1563))
