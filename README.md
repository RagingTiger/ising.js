## About
A modified and dockerized[^fn1] copy of a browser-based Ising Model in Javascript
originally created by user `mattbierbaum`.[^fn2]

## Usage
Below are simple examples of using `Docker`[^fn1] to run a container from the
`tigerj/ising` image. The resulting container (named `ising`) in this example
can be found running at: http://localhost:8080

### Running
```
$ docker run -d --rm --name ising -p 8080:80 tigerj/ising
```

### Stopping
```
$ docker stop ising
```
### Starting
```
$ docker start ising
```

### Removing
```
$ docker rm ising
```

## References
[^fn1]: [Docker](https://docs.docker.com/get-started/)
[^fn2]: [Ising model 2D javascript simulation](https://github.com/mattbierbaum/ising.js)
