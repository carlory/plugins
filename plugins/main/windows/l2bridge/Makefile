

all: $(shell find . -type f -name '*.go')
	GOOS=windows go build -o l2bridge.exe
clean:
	rm -rf l2bridge.exe

