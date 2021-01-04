# isolateTraffic
Isolates a process in its own network namespace/virtual interface, makes it slightly easier to capture traffic from only one process

It's as simple as:
```
./main <command>
```
e.g.
```
./main "ping -c 4 8.8.8.8"
```
