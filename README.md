# prodyn
Generic implementation of the dynamic programming algorithm for optimal system control

[![Documentation Status](https://readthedocs.org/projects/prodyn/badge/?version=latest)](https://prodyn.readthedocs.org/en/latest/) [![DOI](https://zenodo.org/badge/73300738.svg)](https://zenodo.org/badge/latestdoi/73300738)

prodyn [documenation](http://prodyn.readthedocs.org) .

## Features

  * prodyn uses the dynamic programming algorithm to calculate the decision seuqence which leads to minimal total costs
  * prodyn can be apllied to any system function which follows the required structure for inputs and outputs
  * Forward and backward implementation of the dynamic programming algorithm
  * Supports systems with multiple state variables


## Get Started

1. [download](https://github.com/yabata/prodyn/archive/master.zip) or clone (with [git](http://git-scm.com/)) this repository to a directory of your choice.
2. Copy the `prodyn.py` file in the `prodyn` folder to a directory which is already in python's search path or add the `prodyn` folder to python's search path (sys.path) ([how to](http://stackoverflow.com/questions/17806673/where-shall-i-put-my-self-written-python-packages/17811151#17811151))
3. Run the given examples in the `examples` folder.
4. Read the [documenation](http://prodyn.readthedocs.org) and implement your own system function to optimize


## Copyright

Copyright (C) 2016  Dennis Atabay

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>


