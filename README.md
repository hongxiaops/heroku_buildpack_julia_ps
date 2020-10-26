# Julia buildpack for Heroku

This is a [Heroku buildpack][0] for adding a [Julia binary][1] to your environment.


## Versions

* Buildpack: `0.4`
* Julia: `1.5.2`


## Usage

Add this line to the .buildpacks file in your project:

`https://github.com/hongxiaops/heroku_buildpack_julia_ps.git`

or use the command `heroku buildpacks:set`

In your project, create a file `package.jl` with any
Julia code you want to run after installation.

## Thanks
[This orginal repo for heroku julia buildpack](https://github.com/pinx/heroku-buildpack-julia)


[0]: http://devcenter.heroku.com/articles/buildpacks
[1]: http://julialang.org

