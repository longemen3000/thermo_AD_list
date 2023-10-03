# Thermodynamics + Automatic Differentiation

This is a list of repositories that uses Thermodynamics + AD (Automatic Differentiation). Feel free to add your own repository if you use thermodynamics with automatic differenciation. Pull requests are accepted! 

## Clapeyron.jl
- repository: https://github.com/ClapeyronThermo/Clapeyron.jl
- language: julia
- AD: https://github.com/JuliaDiff/ForwardDiff.jl (forward mode, method overloading)

## feos
- repository: https://github.com/feos-org/feos
- language: Rust, python bindings
- AD: https://github.com/itt-ustutt/dualnum (forward mode, method overloading)

## teqp
- repository: https://github.com/usnistgov/teqp
- language: C++, python bindings
- AD: https://github.com/autodiff/autodiff (forward mode used?)

## PyForFluids (branch) 
- repository: https://github.com/fedebenelli/PyForFluids/tree/API_overhaul_autodiff
- language Fortran + python bindings
- AD: https://github.com/google/jax (reverse mode used?)

## CP_PC_SAFT.jl
- repository; https://github.com/vvpisarev/CP_PC_SAFT.jl
- language: julia
- AD: https://github.com/JuliaDiff/ForwardDiff.jl (forward mode, method overloading)

## YaEoS
- repository: https://github.com/fedebenelli/yaeos
- language: Fortran
- AD: https://github.com/fedebenelli/yaeos/blob/main/src/adiff/hyperdual.f90 (forward mode, method overloading)
