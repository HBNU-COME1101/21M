all: Problem
	clang++ -L. answer.o -o answer

Problem: problem.cpp
	clang++ -std=c++11 -c problem.cpp -o answer.o

Solution: problem.sol.cpp
	clang++ -std=c++11 -o solution problem.sol.cpp

clean:
	rm *.o
	rm answer