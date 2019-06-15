main: main.o adder.o
	g++ -o main main.o adder.o

main.o: main.cc header1.h
	g++ -c main.cc

adder.o: adder.cc header2.h
	g++ -c adder.cc

clean:
	rm main main.o adder.o
