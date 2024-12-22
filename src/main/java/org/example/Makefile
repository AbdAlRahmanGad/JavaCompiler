all: compile run

compile:
	javacc java.jj
	javac *.java

run:
	java Java > output.txt