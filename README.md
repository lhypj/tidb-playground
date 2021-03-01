# tiup-playground
Dockerfile for tidb playground using tiup

The image is available at https://hub.docker.com/r/sunnyandpj/tidb_playground.

## Usage

### Build Images

``` bash
docker build -f Dockerfile -t tiup-playground .
```

### Start container

``` bash
docker run -d -p 4000:4000 -p 2379:2379 {image id}
```
