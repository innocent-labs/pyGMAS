pyGMAS is a python package that provides several utilities related to generalized mass action system.
This package was created to plot graphs or estimate parameters of generalized mass action systems.

There may be some errors in the code. We will fix as soon as possible. 
If you notice anything strange, please feel free to contact us at any time.

## Contents

1. Installation
2. How to use
3. License

---
## Installation
pyGMAS can be installed from PyPI using pip
```
pip install pyGMAS
```

---
## How to use
Import gma_system from pygmas.pygmas
```python
from pygmas.pygmas import gma_system, single_to_pyexpr, estimate_parameters
```
Create gma_system object. 
```python
gs = gma_system(gmas, init_concens, t, dt, params)
```
Estimate parameters.
```python
estimate_parameters(gmas, param_list, obs_t, obs_concens, max_iter, intvs)
```

## License
pyGMAS is released under an MIT license.

