This dir has examples for the use of build tags which are very useful just like macros.

##STEPS
- Run `go build -tags 'build1'` to build build1.go
- Run `go build -tags 'build2'` to build build2.go

Another cleaner and useful approach can be
- Run `go build -tags 'build3' -ldflags '-X main.DEBUG=True'` to build build3.go

But notice the difference, you are providing/setting the value of debug at build time.