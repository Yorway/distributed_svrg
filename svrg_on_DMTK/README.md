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
将svrg串行代码，重构后，放入DMTK平台上运行。主要是把AzsLinear类拆分。其读入参数部分，交给Option类去做，读入数据文件部分则交给Reader类去做。
代码可以通过编译，但是有运行时有错误。



