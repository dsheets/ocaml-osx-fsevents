print_events.native: print_events.ml
	ocamlfind ocamlopt -o test -package osx-fsevents,osx-fsevents.lwt,osx-cf.lwt,lwt.unix -linkpkg -thread print_events.ml 

.PHONY: clean
clean:
	rm print_events.native
