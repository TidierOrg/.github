# Tidier

<img src="https://github.com/TidierOrg/.github/raw/main/profile/Tidier_jl_logo.png" align="right" style="padding-left:10px;" width="150"/>

## Welcome to Tidier

Tidier is an organization dedicated to creating tools that make Julia a more
welcoming place for R users familiar with the tidyverse ecosystem. Our flagship
package is [`Tidier.jl`](https://github.com/TidierOrg/Tidier.jl), a 100% Julia
implementation of the R tidyverse mini-language in Julia. In the future, we plan
to convert [`Tidier.jl`](https://github.com/TidierOrg/Tidier.jl) into a meta-package
with smaller base packages that make [`Tidier.jl`](https://github.com/TidierOrg/Tidier.jl)
easier for other package developers to use and build on.

Our roadmap for future packages includes:

- [`Tidier.jl`](https://github.com/TidierOrg/Tidier.jl): This will become a meta-package that re-exports each of the smaller packages.
- `TidierData.jl`: A package dedicated to data transformation, powered by [`DataFrames.jl`](https://github.com/JuliaData/DataFrames.jl),
[`ShiftedArrays.jl`](https://github.com/JuliaArrays/ShiftedArrays.jl), and [`Cleaner.jl`](https://github.com/TheRoniOne/Cleaner.jl).
- `TidierPlots.jl`: A package dedicated to plotting, powered by [`AlgebraOfGraphics.jl`](https://github.com/MakieOrg/AlgebraOfGraphics.jl).
- `TidierTools.jl`: A package aiming to make it easier to create Tidier-style macros that use R-style non-standard evaluation, auto-vectorization, and bang-bang (`!!`) interpolation.
