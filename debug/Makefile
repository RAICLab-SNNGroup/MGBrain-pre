path:
	export LD_LIBRARY_PATH=./:$$LD_LIBRARY_PATH
debug_multi:
	g++ -std=c++11 debug_multi.cpp -L. -lMGPUBrain -o debug_multi
debug_single:
	g++ -std=c++11 debug_single.cpp -L. -lMGPUBrain -o debug_single
clean:
	rm -f *.so *.o debug_multi debug_single