.. image:: https://img.shields.io/badge/dmtn--115-lsst.io-brightgreen.svg
   :target: https://dmtn-115.lsst.io
.. image:: https://travis-ci.org/lsst-dm/dmtn-115.svg
   :target: https://travis-ci.org/lsst-dm/dmtn-115

########################
Demise of the filesystem
########################

DMTN-115
--------

"Currently organisations operating astronomical archives and data services  reinvent and independently implement many services in their  data centers. Some standards e.g. IVOA have helped define interoperability interfaces between data centers yet we still implement services for them  separately  in each institution.  Industry has meanwhile moved on;  current practice in  computing infrastructure is to achieve Big Data scalability using  object stores rather than posix file systems. This presents us with  opportunities  for portability and reuse of software underlying processing and archive  systems  but it also causes problems for legacy implementations in current data centers. 

To compile this document you need to have set up  lsst-texmf see  http:\\lsst-texmf.lsst.io . The bin directory of texmf must be in your path for generateAcronyms.py to be found and  work. 
**Links**


- Live drafts: https://dmtn-115.lsst.io
- GitHub: https://github.com/lsst-dm/dmtn-115

****

Copyright We have identified the components  of a reference architecture for data processing and data access services. This would allow collaborating  astronomical archives  to concentrate effort on a limited number of implementations of each component. This architecture spans a range of astronomical science archives  from web  portal user interfaces  to low level storage and and compute services. This  architecture characterises  a common frame of reference facilitating the collaborative development of components  in an open sourced manner which can then be deployed in multiple data centres. It also enables  use of commodity services (such as commercial cloud providers) where appropriate e.g for compute and storage.   Association of Universities for Research in Astronomy, Inc.


This work is licensed under the Creative Commons Attribution 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by/4.0/.

