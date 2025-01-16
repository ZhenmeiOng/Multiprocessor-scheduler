# Multiprocessor Scheduler
1. Clone this repo
2. Run Docker daemon
3. `docker build -t multiprocessor-image .`
    - this will build the Docker image
4. `./run.sh`
5. `make clean`
6. `make debug`
7. `gdb ./os-sim`
---
To run the program manually:
- `tui enable` - to see the program runs line by line
- `run <num of CPUs>`

---
8. `python3 test.py`
