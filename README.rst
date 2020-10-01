`PSSpred <https://github.com/nickcafferry/PSSpred>`_
===============

|Workflow| |Licence| |Travis| |Codecov| |Appveyor| |Gitter| |Documentation Status| |Circleci|

.. |Workflow| image:: https://github.com/nickcafferry/PSSpred/workflows/PSSpred/badge.svg
   :target: https://github.com/nickcafferry/PSSpred/actions/runs/263139727
   
.. |Licence| image:: https://img.shields.io/badge/license-MIT-blue.svg?style=flat
   :target: http://choosealicense.com/licenses/mit/
   
.. |Travis| image:: https://travis-ci.com/nickcafferry/PSSpred.svg?branch=master
   :target: https://travis-ci.com/nickcafferry/PSSpred
    
.. |Codecov| image:: https://codecov.io/gh/nickcafferry/PSSpred/branch/master/graph/badge.svg
   :target: https://codecov.io/gh/nickcafferry/PSSpred

.. |Appveyor| image:: https://ci.appveyor.com/api/projects/status/j5e243jmixcnqpy2?svg=true
   :target: https://ci.appveyor.com/project/nickcafferry/psspred

.. |Gitter| image:: https://badges.gitter.im/PSSpred/community.svg
   :target: https://gitter.im/PSSpred/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge

.. |Circleci| image:: https://circleci.com/gh/nickcafferry/PSSpred.svg?style=svg
   :target: https://circleci.com/gh/nickcafferry/PSSpred

.. |Documentation Status| image:: https://readthedocs.org/projects/psspred/badge/?version=latest
   :target: https://psspred.readthedocs.io/en/latest/?badge=latest

Copyright |copy| Wei MEI, |MLMS (TM)| |---|
all rights reserved. 
|bamboo|

.. |copy| unicode:: 0xA9 .. copyright sign
.. |MLMS (TM)| unicode:: MLMS U+2122
   .. with trademark sign
.. |---| unicode:: U+02014 .. em dash
   :trim:

.. |bamboo| unicode:: 0x1F024 .. bamboo

A simple neural network training algorithm for accurate `protein secondary structure <https://proteinstructures.com/Structure/Structure/secondary-sructure.html>`_ prediction (PSSpred) !

PSSpred (`Protein Secondary Structure <https://proteinstructures.com/Structure/Structure/secondary-sructure.html>`_ prediction) is a simple neural network training algorithm for accurate `protein secondary structure <https://proteinstructures.com/Structure/Structure/secondary-sructure.html>`_ prediction. It first collects multiple sequence alignments using `PSI-BLAST <https://www.ebi.ac.uk/Tools/sss/psiblast/>`_. Amino-acid frequence and log-odds data with `Henikoff weights <https://www.sciencedirect.com/topics/biochemistry-genetics-and-molecular-biology/structural-property-of-proteins>`_ are then used to train secondary structure, separately, based on the Rumelhart error backpropagation method. The final secondary structure prediction result is a combination of 7 neural network predictors from different profile data and parameters. The program is freely downloadable on this page.

We have a community chat at `Gitter <https://gitter.im/PSSpred/community#>`_. Feel free to ask us anything there. We have a very welcoming and helpful community.

.. raw:: html
   
   <div align="center">
     <img border="0"  src="https://zhanglab.ccmb.med.umich.edu/COVID-19/QHD43415_1.png" width="300">
   </div>

.. raw:: html
   :file: demo.html
