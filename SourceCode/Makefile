CC = g++
CFLAGS = -lglfw -lGLEW -lOpenGL
TARGET = assign5

all: $(TARGET)

$(TARGET): main.cpp
	$(CC) main.cpp $(CFLAGS) -o $(TARGET)

clean:
	rm -f $(TARGET)