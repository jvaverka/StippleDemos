# Demos for Stipple

This repository includes a collection of Stipple demo application.

## Reactive Dashboards with Stipple.jl

Last time, together with the creator of Genie.jl, Adrian Salceanu, we looked into web development with Julia. This time he is back, together with Helmut Hänsel, the two main contributors of Stipple.jl, a package for building interactive reactive dashboards in Julia. Join us and learn how to let your data shine.

After the presentation there will be room for further discussion. Then, as usual for Share&Code, the session will stay open end for everyone to code some Julia, for instance to try out building your own little dashboard application with Stipple.jl.

### Agenda

- 18:30-19:15: Helmut Hänsel (main contributor of Stipple.jl): The Reactive API of Stipple
- 19:15-20:15: Adrian Salceanu (creator of Stipple.jl): Stipple Extensions - StippleUI, StipplePlotly and Demos
- 20:15 - open end: Let's code together

### Materials

[slides](https://docs.google.com/presentation/d/1_G_MqbE_f0BZpt82aaIniPkkWDZ3zehuWD2K5e-mCsY/edit#slide=id.gd6b83345a5_0_8)

## Set up

1. Download or clone demos repo

2. Open a Julia REPL (Start Julia from Start menu, app launcher, terminal, Applications folder, etc)

3. `cd` to the demos folder. Ex: `julia> cd("<path_to_demos_folder_>")`

4. Go into package management mode and run `pkg> activate .` and `pkg> instantiate` (type `julia> ]` to enter `pkg` mode)

## Run the demos

1. Open a Julia REPL (Start Julia from Start menu, app launcher, terminal, Applications folder, etc)

2. `cd` to the demos folder. Ex: `julia> cd("<path_to_demos_folder_>")`

3. Activate the environment - press `]` to go into `pkg> ` mode and run

  ```julia
  pkg> activate .
  ```

  then exit `pkg> ` mode (via Ctrl+C or backspace until the cursor changes from `pkg> ` to `julia> `)

4. Run:

```julia
julia> include("IrisClustering.jl") # swap "IrisClustering.jl" with any other demo
```

Upon starting the application, a browser window should automatically open with the demo dashboard.
