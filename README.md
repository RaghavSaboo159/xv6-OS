# xv6-OS
uploaded the pdf in which i have written the changes which i have done to the original xv6 OS.
exclude the bonus part

# REQUIREMENTS
QEMU 3.0 or above

# START
make clean

make SCHEDPOL "flag"

make qemu -nox SCHEDPOL "flag"
## flag
1. DEFAULT - for round robin
2. PBS     - for priority based scheduling
3. FCFS    - for first come first serve scheduling
4. MLFQ    - for multilevel feedback queue scheduling
