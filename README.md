CIFReader
=========

This is a Java version of CIFReader, a previous project written in C++ used to serve my needs. Many people (myself included) felt that it was a bit of a kludge and an absolute arse to build. So here's a Java version. I invite anyone to take over the C++ project, as this will be the primary project moving on.

Please contact me if you use the software, I'd love to know where. Email address is tom@swlines.co.uk.

Licence
-------

CIFReader (Java) and it's source is licenced under Affero GPL. 

Requirements
------------

- Java 1.6+
- In the future, some sort of database library.
  - I'll support MySQL initially.
  - Then probably MongoDB. (I use both of these at the moment)

File formats supported
----------------------
CIFReader was built to support Network Rail's CIF format. In the future, ATCO CIF will also be supported. 

Therefore, as a roadmap:

- Rail industry (Network Rail) CIF
- followed quickly by ATOCs slight modification of CIF
- ATCO CIF (used primarily in NPTDR)
- TransXChange