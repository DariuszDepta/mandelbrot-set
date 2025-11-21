# Mandelbrot

```shell
$ time ./target/release/mandelbrot mandel.png 4000x3000 -1.20,0.35 -1,0.20
```

```text
real    0m2,609s
user    0m2,554s
sys     0m0,044s
```

```shell
$ time ./target/release/mandelbrot mandel.png 10000x8500 -2.5,-1.5 1.0,1.5
```

```text
real    0m1,982s
user    0m8,527s
sys     0m0,220s
```
