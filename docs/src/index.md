# ABC.jl:  Approximate Bayesian Computing for Julia

This package provides for Approximate Bayesian Computing (ABC) via sequential importance sampling in Julia.  
Currently, it implements a single algorithm, ABC-PMC based on Beaumont et al. 2002 via abc_pmc_plan_type.
However, it does include several extra features that will eventually be documented. 


## Getting Started
 
- Add the ABC package (update once become registered)
- using ABC
- include("tests/runtests.jl")
- See test1.jl for a demo of how to use ABC
 
## API

```@autodocs
Modules = [ABC]
Private = false
Order   = [:module, :function, :type]
```

## Index
 
```@index
```

