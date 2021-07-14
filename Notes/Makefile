PREFIX?=/usr
BIN?=$(PREFIX)/bin

default:
	@printf "Usage:\n\tmake install\tinstall notit\n\tmake uninstall\tuninstall notit\n"
install:
	install -Dm755 notit $(BIN)/notit
uninstall:
	rm -f $(BIN)/notit
