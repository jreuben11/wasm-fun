# wasm-fun

## setup environ
```
git clone https://github.com/juj/emsdk.git
cd emsdk
./emsdk install --build=Release sdk-incoming-64bit binaryen-master-64bit
./emsdk activate --global --build=Release sdk-incoming-64bit binaryen-master-64bit
source ./emsdk_env.sh

npm install -g node-static
```
## compile
`emcc hello.c -s WASM=1 -o hello.html`

## status
`static`
http://localhost:8080/hello.html
