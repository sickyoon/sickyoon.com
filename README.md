# blog

Blog based on Hugo

## Sync

Sync recursively or update submodule

```
git clone --recursive https://github.com/sickyoon/sickyoon.com.git
```

```
git submodule init
git submodule update
```

## Docker run
```
docker build -t blog:latest .
docker run --rm -it -v $PWD:/src -p 1313:1313 blog:latest --bind=0.0.0.0
```

## Github Publishing
Push `/public/` directory to sickyoon.github.io

## Libraries

* Minify (https://dl.equinox.io/tdewolff/minify/stable)

