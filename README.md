Porkchop
========

Porkchop is a simple network-based dictionary server. You write plugins
for it and it responds with the data based on your request.

Here is an example:

    scott@beatbox:~% curl http://localhost:3000/cpuinfo
    /cpuinfo/processor2/fpu yes 
    /cpuinfo/processor2/f00f_bug no
    /cpuinfo/processor2/cache_alignment 64
    /cpuinfo/processor2/vendor_id AuthenticAMD
    /cpuinfo/processor2/flags fpu 
    /cpuinfo/processor2/bogomips 6384
    /cpuinfo/processor2/hlt_bug no
    /cpuinfo/processor2/apicid 2
    /cpuinfo/processor2/fpu_exception yes 
    /cpuinfo/processor2/stepping 3
    /cpuinfo/processor2/wp yes 
    /cpuinfo/processor2/siblings 4
    /cpuinfo/processor2/model 4
    /cpuinfo/processor2/coma_bug no
    /cpuinfo/processor2/fdiv_bug no
    /cpuinfo/processor3/fpu yes 
    /cpuinfo/processor3/f00f_bug no
    /cpuinfo/processor3/cache_alignment 64
    /cpuinfo/processor3/vendor_id AuthenticAMD
    /cpuinfo/processor3/flags fpu 
    /cpuinfo/processor3/bogomips 6384
    /cpuinfo/processor3/hlt_bug no
    /cpuinfo/processor3/apicid 3
    /cpuinfo/processor3/fpu_exception yes 
    /cpuinfo/processor3/stepping 3
    /cpuinfo/processor3/wp yes 
    /cpuinfo/processor3/siblings 4
    /cpuinfo/processor3/model 4
    /cpuinfo/processor3/coma_bug no
    /cpuinfo/processor3/fdiv_bug no
    [snip]
    /time 1311387215
    scott@beatbox:~%
