Distributed SVRG
==========

The Distributed SVRG tool is a parallelization of the SVRG algorithm on top of DMTK parameter server. It provides an efficient "scaling to industry size" solution for SVRG.

For more details, please view the DMTK website [http://www.dmtk.io](http://www.dmtk.io).

Build
----------

**Linux** (Tested on TianHe 1)

Run $./build.sh to build the project.

Run $./example/run.sh to run the project. 


V2.0
==========
规范代码格式，删除多余的头文件、变量等。通过编译。
在一个进程里只有一个线程trainer的前提下，该代码可以跑多进程。但由于数据没有切分，每个进程跑的数据集是一样的。



