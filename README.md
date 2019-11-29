# xv6-OS
# START
make clean
make SCHEDPOL "flag"
make qemu -nox SCHEDPOL "flag"
## flag
1. DEFAULT - for round robin
2. PBS     - for priority based scheduling
3. FCFS    - for first come first serve scheduling
4. MLFQ    - for multilevel feedback queue scheduling
