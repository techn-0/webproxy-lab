# echoclient만 파일명에 맞게 바꿔주면 됨.
TARGET = echoserveri
OBJS = 	echoserveri.o csapp.o

%.o: %.c
	gcc -c $<

$(TARGET) : $(OBJS)
	gcc -o $(TARGET) $(OBJS) -lpthread

clean:
	rm -f *.o
	rm -f $(TARGET)
