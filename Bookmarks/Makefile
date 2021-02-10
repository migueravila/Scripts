PREFIX?=/usr
BIN?=$(PREFIX)/bin

default:
	@printf "Usage:\n\tmake install\tinstall bmwb\n\tmake uninstall\tuninstall bmwb\n"
install:
	install -Dm755 bmwb $(BIN)/bmwb
uninstall:
	rm -f $(BIN)/bmwb
