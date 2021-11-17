main:multi_simple multi_counter multi_vogel
	echo "compile complete"
multi_simple:
	g++ -std=c++11 multi_simple.cpp -L. -lMGPUBrain -o multi_simple
multi_counter:
	g++ -std=c++11 multi_counter.cpp -L. -lMGPUBrain -o multi_counter
multi_vogel:
	g++ -std=c++11 multi_vogel.cpp -L. -lMGPUBrain -o multi_vogel
clean:
	rm -f *.o *.so multi_simple multi_counter multi_vogel