.PHONY: run
run: _build/default/program.exe
	_build/default/program.exe

_build/default/program.exe: $(wildcard *.ml) $(wildcard *.mli)
	dune build program.exe
