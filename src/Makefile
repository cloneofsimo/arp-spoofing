LDLIBS=-lpcap -pthread


all: arp-spoofing

arp-spoofing: main.o arphdr.o ethhdr.o ip.o mac.o
	$(LINK.cc) $^ $(LOADLIBES) $(LDLIBS) -o $@

clean:
	rm -f arp-spoofing *.o *~ 
