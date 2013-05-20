此脚本用来测试MySQL Server的性能。主要参考了Axel Schwenke所写的\ `MariaDB`_
`Benchmark`_\ 的脚本。

所使用的工具为： `sysbench 0.5`_

.. _sysbench 0.5: https://launchpad.net/sysbench
.. _MariaDB: https://mariadb.org/
.. _Benchmark: https://code.launchpad.net/~ahel/maria/mariadb-benchmarks

settings        设置一些与测试相关的参数
run.sysbench    运行测试操作
collect         收集测试数据用于gnuplot作图

