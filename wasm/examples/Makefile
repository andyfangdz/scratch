all: hello

hello: hello.c
	emcc hello.c -s WASM=1 -o hello.html

clean:
	rm -rf *.js *.html *.bc *.wasm

run:
	emrun --browser=chrome --port 8080 .