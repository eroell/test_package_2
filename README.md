## test-package-2

Followed this tutorial here:
https://packaging.python.org/en/latest/tutorials/packaging-projects/

Compared to the other test-package, here no setup.py is used, but a pyproject.toml file is required.

Also compared to the other test-package, there the building of built distribution (wheel, .whl) and the source distribution (sdist, .tar.gz) is done with python3 setup.py sdist bdist_wheel. Here, this is done with  python3 -m build (in the directory where the pyproject.toml file is)
