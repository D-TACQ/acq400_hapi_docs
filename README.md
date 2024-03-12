![Logo](https://www.d-tacq.com/images/dtacq.png)

D-Tacq [acq400_hapi](https://github.com/D-TACQ/acq400_hapi) documentation

[online docs](https://D-TACQ.github.io/acq400_hapi_docs/)

### Dependencies:

* [Sphinx](https://www.sphinx-doc.org/en/master/usage/installation.html)
* [sphinx-argparse](https://sphinx-argparse.readthedocs.io/en/latest/install.html)
* [sphinx-design](https://sphinx-design.readthedocs.io/en/rtd-theme/)
* [sphinx-rtd-theme](https://sphinx-rtd-theme.readthedocs.io/en/stable/installing.html)

### How To

Install dependencies:
```
    apt install python3-sphinx

    pip3 install sphinx-argparse
    pip3 install sphinx-design
    pip3 install sphinx-rtd-theme
    pip3 install pykeystore pyepics
    pip3 install flask
    pip3 install pyepics
    pip3 install xlsxwriter
    pip3 install libpasteurize
    pip3 install pasteurize
    pip3 install prettytable pykeystore


    sudo apt install python3-matplotlib
    sudo apt install python3-flask
    sudo apt install python3-psutil
    sudo apt install python3-xlsxwriter
    sudo apt install python3-future
```

Clone and Run:
```
    git clone https://github.com/D-TACQ/acq400_hapi_docs
    cd acq400_hapi_docs
    ./make_docs.sh
```

Push updated docs to master branch:

```
    git add docs/
    git commit -m 'made from repo at commit <HASH>'
    git push
```

