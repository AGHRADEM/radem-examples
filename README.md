# radem-examples

```
git clone --recurse-submodules git@github.com:AGHRADEM/radem-examples.git
cd radem-examples
python -m venv venv
source venv/bin/activate

pip install -e external/radem
pip install -r requirements.txt
python -c "import radem; print(radem.__version__)"
```
