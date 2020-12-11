PREFIX?=/usr
BIN?=$(PREFIX)/bin

default:
	@printf "Usage:\n\tmake install\tinstall bmrp\n\tmake uninstall\tuninstall bmrp\n"
install:
	install -Dm755 bmrp $(BIN)/bmrp
uninstall:
	rm -f $(BIN)/bmrp
