# iter-together-2

This package has some utilities for iterating over files

## Getting Started

```python
from iter_together.utils import iter_together_file

file_1 = ['hi', 'hello']
file_2 = ['goodbye', 'cheers']
results = iter_together_file(file_1, file_2)
```

## Installation

The code can be installed from GitHub with:

```shell
$ pip install git+https://github.com/cthoyt-teaches-reproducibility/iter-together-2.git
```

The code can be installed in development mode with:

```shell
$ git clone https://github.com/cthoyt-teaches-reproducibility/iter-together-2.git
$ cd iter-together-2
$ pip install --editable .
```

Where `--editable` means the code is symlinked into your environment's site-packages directory.

## License

This code is licensed under the MIT license.
