OCAML_FIND ?= ocamlfind

build:
	ocamlbuild -use-ocamlfind extended_map.cma extended_map.cmxa extended_map.a

clean:
	ocamlbuild -use-ocamlfind -clean

install:
	$(OCAML_FIND) install extended_map META \
	_build/extended_map.cma \
	_build/extended_map.cmxa \
	_build/extended_map.cmi \
	_build/extended_map.mli \
	_build/extended_map.a


uninstall:
	$(OCAML_FIND) remove extended_map


default: build
