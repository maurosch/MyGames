#OBJS specifies which files to compile as part of the project
OBJS = src/*.cpp src/*.cc

#CC specifies which compiler we're using
CC = g++

#COMPILER_FLAGS specifies the additional compilation options we're using
# -w suppresses all warnings
COMPILER_FLAGS = -w -std=c++11 -g

#LINKER_FLAGS specifies the libraries we're linking against
LINKER_FLAGS = -lprotobuf -lSDL2 -lSDL2_image -lSDL2_ttf -lSDL2_mixer -lSDL2_net

#OBJ_NAME specifies the name of our exectuable
OBJ_NAME = game

all: $(OBJS)
	$(CC) $(OBJS) $(COMPILER_FLAGS) $(LINKER_FLAGS) -o $(OBJ_NAME)
