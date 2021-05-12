# zxsh

Shell scripts made simple 🐚

Inspired by Google's [zx](https://github.com/google/zx), but made much simpler and more accessible using bash.

``` sh
#!/usr/bin/env zxsh

cat package.json | grep name

dep deploy --branch=$(git branch --show-current)
```

## install

``` sh
ln -s $(which bash) /usr/local/bin/zxsh
```

## Documentation

```sh
man bash
```
