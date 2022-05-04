CFLAGS+=	-Wall -I/usr/local/include
LDFLAGS+=	-L/usr/local/lib/ -lssh2

all: sshcrack

sshcrack: sshcrack.o lists.o ssh.o
	$(CC) sshcrack.o lists.o ssh.o $(LDFLAGS) -o sshcrack

sshcrack.o: sshcrack.c

lists.o: lists.c

ssh.o: ssh.c

clean:
	rm *.o sshcrack
