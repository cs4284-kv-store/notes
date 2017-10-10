# Notes
This repository is for notes about our project.

We can stream data indefinitely with redis-benchmark
```
docker run -it --rm --link redis:redis clue/redis-benchmark -t set -l -c 1
docker run -it --rm --link redis:redis clue/redis-benchmark -t get -l -c 1
```

https://www.tutorialspoint.com/redis/redis_benchmarks.htm
