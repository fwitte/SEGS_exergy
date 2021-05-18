Exergy Analysis of a Solar Thermal Power Plant in TESPy
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Example for the exergy analysis in `TESPy <https://github.com/oemof/tespy>`_.
Find more information about the exergy analysis feature in the respective
`online documentation <https://tespy.readthedocs.io/>`_.

The Solar Energy Generating System (SEGS) model has the following topology:

.. figure:: ./flowsheet_TESPy.svg
    :align: center
    :alt: Topology of the Solar Energy Generating System (SEGS) in TESPy

Find the model specifications and results in the SEGS.py script and the
corresponding `pdf model report <SEGS_model_report.pdf>`_.

Usage
-----
Clone the repository and build a new python environment. From the base
directory of the repository run

.. code-block:: bash

    pip install -r ./requirements.txt

to install the version requirements for the SEGS.py python script.

On top of the python script, an EBSILON model (v14.03.01) for the identical
setup is provided for validation. The results are available in the respective
flowsheet. The solar field is not considered for further investigation, thus it
represents a heat input only.

.. figure:: ./flowsheet_EBSILON.svg
    :align: center
    :alt: Topology of the Solar Energy Generating System (SEGS) in EBSILON

The original data of the plant are partially obtained from the following
reports:

*F. Lippke, Simulation of the part-load behavior of a 30 MWe SEGS plant,
Technical Report SAND-95-1293, Sandia National Lab., Albuquerque, 1995.
URL:https://www.osti.gov/biblio/95571. doi:10.2172/95571.*

*D. Kearney, C. E. Miller, Technical Evaluation of Project Feasibilty for
SEGS VI, Technical Report,1988. Submitted to Luz Solar Partners VI.*

Citation
--------
The state of this repository is archived via zenodo. If you are using the
TESPy model within your own research, you can refer to this model via the
zenodo doi: `10.5281/zenodo.4769203 <https://zenodo.org/record/4769203>`_.

MIT License
-----------

Copyright (c) 2021 Francesco Witte, Julius Meier, Ilja Tuschy,
Mathias Hofmann

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
