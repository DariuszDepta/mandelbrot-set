# Colorful Mandelbrot set generator

## Examples

![mandel](./mandel.png)

![mandel-big](./mandel-big.png)

## Performance

### Limit set to **10 000**.

Commands:

```shell
$ cargo build --release
$ time ./target/release/mandelbrot-set mandel.png 4000x3000 -1.20,0.35 -1,0.20
```

Output:

```text
real    0m13.621s
user    0m0.000s
sys     0m0.000s
```

Commands

```shell
$ cargo build --release
$ time ./target/release/mandelbrot-set mandel-big.png 10000x8500 -2.5,-1.5 1.0,1.5
```

```text
real    0m56.151s
user    0m0.000s
sys     0m0.000s
```
