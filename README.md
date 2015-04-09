# static-buildpack
A simple CF buildpack created for illustrative purposes.

## Usage
```
$ cd
$ mkdir static-demo
$ cd static-demo
$ cat > "index.html" << EOF
<p>Hello World!</p>
EOF
$ cf push static -b https://github.com/michaljemala/static-buildpack.git --random-route
```
