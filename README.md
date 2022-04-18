#include "SDL.h"
#include "stdio.h"

class Game
{
public:
Game();
SDL_Window* Window;

}

Game::Game()
{
Window=NULL;
}

int main(int argc,char args[])
{
if(SDL_Init(SDL_INIT_VIDEO==0)
{
Window=SDL_CreateWindow("GAME",SDL_WINDOWPOS_CENTERED,SDL_WINDOWPOS_CENTERED,748,640,SDL_WINDOW_FULLSCREEN_DESKTOP);
}
SDL_Delay(5000);
return 0;

}
