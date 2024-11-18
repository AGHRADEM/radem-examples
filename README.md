## Examples for the radem library
A collection of example jupyter notebooks demonstrating how to use the radem library. This repository provides practical use cases and tutorials for leveraging the features of radem, with the library included as a Git submodule for easy integration and testing.

## How to install?
Firstly clone the repository and it's submodules:
```
git clone --recurse-submodules git@github.com:AGHRADEM/radem-examples.git
cd radem-examples
```

Next create a virtual enviroment for python
```
python -m venv venv

source venv/bin/activate # For MacOS/Linux
.\venv\Scripts\activate  # For Windows
```

Now you should be able to install the library and test
```
pip install -e external/radem
python -c "import radem; print(radem.__version__)"
```

## Index
In the `examples/` directory you'll find a list of example jupyter notebooks with tutorials on how to use the radem library.
1. `data_conversions.ipynb` - This notebook showcases methods for loading and saving data into different formats
2. `total_gcr_dose.ipynb` - Describes the methods for detecting SEP events in the datas
