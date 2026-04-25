### show command XR

```sh
show bgp ipv4 unicast neighbors
```
```sh
show bgp ipv4 unicast summary
```
<pre>
Neighbor        Spk    AS MsgRcvd MsgSent   TblVer  InQ OutQ  Up/Down  St/PfxRcd
10.255.255.28     0 132080 5259073  113925        0    0    0    26w6d Active
10.255.255.33     0 132080 8296727 96774796 565327368    0    0    16w6d          9
100.64.3.133      0 38235 211284792  251990 565327368    0    0    16w4d    1073658
100.64.3.137      0 38235  288468  252052 565327368    0    0    16w4d          5
103.136.21.255    0 132080 96492983 96426477 565327368    0    0    24w5d    1080927
172.16.168.17     0 150381 4281667 63158863 565326724    0    0     8w2d          3
172.27.254.21     0 24492  292477  249749 565327368    0    0     6w0d          2
202.79.31.9       0 24492 116204598  249754 565327368    0    0    12w6d    1055568
</pre>


###  commit confirmed minutes x

```sh
 commit confirmed minutes 6
```
<pre>
 commit confirmed minutes 6
 
! it will rollback the previous after 6 minutes
! Verify new setup
ping
</pre>

