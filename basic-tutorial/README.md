## Usage

    make -j

============rdma_test============

In one server (e.g. worker2):
    ./rdma_demo_1side ib5 writer

In another server (e.g. worker5)
    ./rdma_demo_1side ib2 reader

============benchmark============

In one server (e.g. worker2):
    ./rdma_demo_2side ib5 writer

In another server (e.g. worker5)
    ./rdma_demo_2side ib2 reader

