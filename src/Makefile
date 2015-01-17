bloomfilter: mmapbitarray.* bloomfilter.*
	gcc -lm -O3 -lstdc++ mmapbitarray.c md5.c MurmurHash3.cpp bloomfilter.c -o bf

mbarray: mmapbitarray.*
	gcc -lm -O3 -lstdc++ -DMBAQUERY mmapbitarray.c -o mbaquery
	gcc -lm -O3 -lstdc++ -DMBACREATE mmapbitarray.c -o mbacreate
