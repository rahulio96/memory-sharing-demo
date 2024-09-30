# Memory Sharing Demo
Practicing OS fundamentals

## Compile
`gcc src/consumer.c -lrt -o bin/consumer`

`gcc src/producer.c -lrt -o bin/producer`

## Execute
`cd ./bin`

`./producer <buffer size> <item count> <random seed>`