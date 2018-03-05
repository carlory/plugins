

all: $(shell find . -type f -name '*.go')
	GOOS=windows go build -o overlay.exe
clean:
	rm -rf overlay.exe

