# Memory Sharing Demo
Practicing OS fundamentals by recreating the producer consumer paradigm using a
shared memory block for IPC. No process synchronization, so we leave one empty spot
in the shared memory buffer to prevent issues.

## Compile
```bash
gcc src/consumer.c -lrt -o bin/consumer
```

```bash
gcc src/producer.c -lrt -o bin/producer
```

## Execute
```bash
cd ./bin
```

```bash
./producer <buffer size> <item count> <random seed>
```