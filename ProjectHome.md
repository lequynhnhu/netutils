'netuils' is a Java library that combines several useful functionalities for various network traffic research tasks. <br>
It is written mostly in Java and therefore easy and fast to develop compared<br>
to C/C++ (although C/C++ fans might not think so).<br> The library also has the advantage of<br>
multi-platform support. <br>The 'netutils' package gives a low level java network library.<br>
It contains extensive infrastructure for sniffing, injecting, building and parsing Ethernet/IP/TCP/UDP/ICMP<br>
packets.<br> The library is based (using JNI - Java Native Interface) on two multi platform well known c libraries: libnet and libpcap. libnet is used for injection while libpcap is used for recording/snffing.<br>
The package also includes pure java packages for parsing and reading/writing to/from capture files<br>
using the libpcap format (and some other formats).<br>  'netutils' was written during my thesis, mainly for network traffic analyze and partly for running<br>
simple tests which included traffic injection.<br> The library contains extensive and reach IP based (mainly TCP and UDP) parsing functionality and capture files manipulations. It also includes flow level abstraction and <b>support ipv6</b> parsing. <br>
'netutils' injection and sniffing performance capability<br>
is limited and could not be used with high line rate, but it is good enough for small to medium<br>
tests (when recording the real bootle neck is usually the disk)<br>
<br>
<b>sniffing and injecting is not supported currently as it is not updated (no time)</b><br>
<b>looking for a partner to integrate rocksaw into it</b><br>
<b>meanwhile I suggest using rocksaw, a great library for sniffing and injecting</b><br>