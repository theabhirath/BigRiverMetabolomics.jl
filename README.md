# BigRiverMetabolomics.jl

*A Toolbox for Metabolomics Analysis*

`BigRiverMetabolomics.jl` is a package that is designed to be a comprehensive toolbox designed to simplify and accelerate metabolomics data analysis. It contains three different aspects that together form a complete metabolomics analysis pipeline:

- **Preprocessing**: This includes data imputation, normalization, transformation and standardization, all provided with the help of the [`BigRiverJunbi.jl`](https://github.com/senresearch/BigRiverJunbi.jl) package.
- **Statistical Analysis**: This includes functions for performing statistical analyses, using both supervised approaches like matrix methods (provided by [`MatrixLM.jl`](https://github.com/senresearch/MatrixLM.jl)) and unsupervised approaches like PCA or PLSDA.
- **Visualization**: This includes functions for visualizing the results of the statistical analyses, using the [`BigRiverMakie.jl`](https://github.com/senresearch/BigRiverMakie.jl) package.

## Installation

To install BigRiverMetabolomics.jl, you can use Julia's package manager:

```julia
using Pkg
Pkg.add("https://github.com/senresearch/BigRiverMetabolomics.jl")
```

or you can use the built-in package manager mode in the Julia REPL:

```julia
] add https://github.com/senresearch/BigRiverMetabolomics.jl
```
