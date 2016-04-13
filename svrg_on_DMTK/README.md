Distributed SVRG
==========

The Distributed SVRG tool is a parallelization of the SVRG algorithm on top of DMTK parameter server. It provides an efficient "scaling to industry size" solution for SVRG.

For more details, please view the DMTK website [http://www.dmtk.io](http://www.dmtk.io).

Build
----------

**Linux** (Tested on TianHe 1)

Run $./build.sh to build the project.

Run $./example/run.sh to run the project. 


V1.0
==========
加入对数据切分的支持。
在一个进程里只有一个线程trainer的前提下，该代码可以数据并行多进程执行。