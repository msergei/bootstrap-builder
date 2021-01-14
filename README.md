# SASS Bootstrap builder with docker-compose 

## Build instruction

To build bootstrap from source you need to do a few simple steps:

1. Pull bootsrtap repo: ```git submodule update --init --recursive --remote```

2. Install docker and docker-compose

3. You can modify variables to set customised screen resolutions, for example, scss/_variables.scss:

```
$grid-breakpoints: (
  xs: 0,
  sm: 576px,
  md: 768px,
  lg: 992px,
  xl: 1200px,
  xxl: 1400px,
  xxxl: 1600px,
  hd: 1920px,
  2k: 2560px,
  3k: 3200px,
  4k: 4096px,
  5k: 5120px,
  6k: 6400px,
  7k: 7680px,
  10k: 10240px
) !default;

$container-max-widths: (
  sm: 540px,
  md: 720px,
  lg: 960px,
  xl: 1140px,
  xxl: 1320px,
  xxxl: 1520px,
  hd: 1840px,
  2k: 2460px,
  3k: 3120px,
  4k: 4000px,
  5k: 5100px,
  6k: 6300px,
  7k: 7580px,
  10k: 10100px
) !default;

```


4. docker-compose up

5. In css/ folder get your bootstrap.css 