# GOSTATIC

A static file server built using golang's native http module

run using:
```sh
make dev
```

build using:
```sh
make build
```

binary can be found in `bin/gostatic`

to make it directly accessible move it to bin
```sh
sudo mv bin/gostatic /usr/local/bin
```
then run: `gostatic`

accepts two flags:
* `-p` : port to run the file server on, ex: `-p 6969` - defaults to `8100`
* `-d` : path to run the file server on, ex: `-d ./vids/movies` - defaults to `.` as in the current directory

