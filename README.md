# MySDL2
汇集了sdl源码和编译版本，方便取用

qt中引入库，在pro文件中
SDL_HOME = $$PWD/SDL2/SDL2-2.0.22
INCLUDEPATH += $${SDL_HOME}/include
LIBS += -L$${SDL_HOME}/lib/x64 \
            -lSDL2