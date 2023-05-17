# FCDN-CLIENT

Fastest file downloader for a same file on a 2 different server

# Build
If you are on x86 or x64 architecture so you can download pre-build source 

or directly build for your architecture
Linux: 
```bash
  # Require Golang 1.2 +
  go build src/fcdn.go
  chmod +x src/fcdn # Giving permision for execute 
  mv src/fcdn | fcdn &
```
Windows: 
```bash
  go build src/fcdn.go
  cd src
  ./fcdn
```
Demo: 
https://github.com/pawitpr/fcdn-client/assets/123424956/df629a88-0ff8-4c51-8c96-bee81d40c5f7
and in this video also include the benchmark(normal download vs multi source download)
