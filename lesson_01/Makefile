THEME=ISMT

structure: structure.md
	pandoc -t latex $^ -o structure.pdf

assignment: assignment.md
	pandoc -t beamer $^ -V theme:$(THEME) -o assignment.pdf

all: structure assignment
