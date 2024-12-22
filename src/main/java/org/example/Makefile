all: compile run

compile:
	javacc java.jj
	javac *.java

run:
	java Java > output.txt

clean:
	rm -f *.class Java.java JavaTokenManager.java JavaConstants.java ParseException.java Token.java SimpleCharStream.java output.txt