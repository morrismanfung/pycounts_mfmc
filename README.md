# pycounts_mfmc

Individual assignment 1 for DSCI 524. Package is created based on [https://py-pkgs.org/03-how-to-package-a-python#package-documentation](https://py-pkgs.org/03-how-to-package-a-python#package-documentation).

## Installation

```bash
$ pip install pycounts_mfmc
```

## Usage

`pycounts_mfmc` can be used to count words in a text file and plot results
as follows:

```python
from pycounts_mfmc.pycounts_mfmc import count_words
from pycounts_mfmc.plotting import plot_words
import matplotlib.pyplot as plt

file_path = "test.txt"  # path to your file
counts = count_words(file_path)
fig = plot_words(counts, n=10)
plt.show()
```

## Contributing

Interested in contributing? Check out the contributing guidelines. Please note that this project is released with a Code of Conduct. By contributing to this project, you agree to abide by its terms.

## License

`pycounts_mfmc` was created by Morris Chan based on `pycounts` by Toma Beuzen. It is licensed under the terms of the MIT license.

## Credits

`pycounts_mfmc` was created with [`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and the `py-pkgs-cookiecutter` [template](https://github.com/py-pkgs/py-pkgs-cookiecutter).
