# ipython-importer

Enables importing IPython notebooks as Python modules.

IPython is great, but oftentimes has trouble scaling to more complex projects. Normally, you'd just split a Python file into smaller files and import them, but you can't import an IPython notebook like a Python file. Well, now you can! 

# Installation

1. Clone this repository (`git clone https://github.com/zplizzi/ipython-importer.git`)
2. Navigate into the root directory of this repo (`cd ipython-importer`)
3. Run `python setup.py install`

# Usage

1. Import with `import ipython_importer`
2. Now you can import `.ipynb` files just like you would normal `.py` files, like `import my_cool_module`.
