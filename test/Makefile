path:
	export LD_LIBRARY_PATH=../:$$LD_LIBRARY_PATH

simple:
	g++ -o $@ test_simpleben.cpp -L.. -lMGPUBrain -std=c++11

counter:
	g++ -o $@ test_counter.cpp -L.. -lMGPUBrain -std=c++11

multinn:
	g++ -o $@ test_multinn.cpp -L.. -lMGPUBrain -std=c++11

resume:
	g++ -o $@ test_resume.cpp -L.. -lMGPUBrain -std=c++11

clean:
	rm -f *.so *.o counter multinn resume simple
