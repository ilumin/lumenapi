# lumenapi

```
	lumen-api ❯❯❯ docker run -it --rm --net=lumenapi_default ilumin/wrk -t12 -c400 -d30s http://172.19.0.2/test-param/ilumin 
	Running 30s test @ http://172.19.0.2/test-param/ilumin
	  12 threads and 400 connections
	  Thread Stats   Avg      Stdev     Max   +/- Stdev
	    Latency   883.09ms  474.18ms   2.00s    71.91%
	    Req/Sec    20.72     17.59   245.00     83.10%
	  4923 requests in 30.09s, 1.28MB read
	  Socket errors: connect 0, read 0, write 0, timeout 744
	  Non-2xx or 3xx responses: 53
	Requests/sec:    163.61
	Transfer/sec:     43.56KB
```
