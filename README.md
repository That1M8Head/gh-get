# gh-get
A `git clone` wrapper that makes it simple to clone any GitHub repository.

### Building
Clone the repo (unfortunately you can't use `gh-get` to download `gh-get` if you don't have it yet):
```
> git clone https://github.com/That1M8Head/gh-get
> cd gh-get
```
Use your favourite C compiler to compile it:
```
> gcc -o gh-get gh-get.c
```
And you're done! You can go ahead and `cp` it to `/usr/local/bin/` or wherever else you want.

### Using gh-get
```
gh-get [https|ssh] <username> <repo> [destination]
```
If neither `https` nor `ssh` are specified, `gh-get` will use HTTPS by default.

### Examples
```
> gh-get that1m8head gh-get
```
```
> gh-get https id-Software DOOM
```
```
> gh-get ssh Rick-Lang rickroll-lang
```
```
> gh-get thiderman doge ~/doge
```
