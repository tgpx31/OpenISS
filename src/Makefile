SHELL:=/bin/bash
CC=gcc
CFLAGS= - g -WALL

EXE=build
OBJ=el6

all: $(EXE) $(OBJ)
	cd scripts; \
		./$(EXE).sh $(OBJ)

clean: $(EXE)
	cd scripts; \
	./$(EXE).sh --cleanup 

$(EXE):
$(OBJ):
