SO=nethello.so
CFLAGS=-g -fPIC -I../..
LDFLAGS=-g -fPIC -shared
OBJS = \
	nethello.o

all: $(SO)

clean:
	$(RM) $(OBJS) $(SO)

$(SO): $(OBJS)
	$(CC) -o $(SO) $(OBJS) $(LDFLAGS)
