#include <kipr/botball.h> 
#include "Alexandria.h"
int main() 
{//Begin int 
    wait_for_light(0);
    shut_down_in(115);
    
    printf("Hello World\n"); 
    
    printf("Task 2 commence\n");
    Vroom(800,800,6400);
    Vroom(-800,-800,5400);
    Vroom(-800,0,2000);
    Vroom(800,0,5000);
	Vroom(-800,-800,1000);
    Vroom(-800,0,1000);
    Vroom(800,0,2900);
	Vroom(800,800,2000);
    
    cmpc(0);
	while(gmpc(0)<2200)
	{
    	Vroom(2000,0,0);
    	msleep(500);
    	Vroom(0,2000,0);
    	msleep(500);
	}

	Vroom(0,800,5600);
    Vroom(800,800,2900);
    Vroom(800,0,2900);
    Vroom(800,800,3000);
    Vroom(0,800,2900);
	Vroom(800,800,2900);
    
    Vroom(-800,0,2000);
    Vroom(800,0,5000);
	Vroom(-800,-800,1000);
    Vroom(-800,0,1000);
    Vroom(800,0,2900);
	Vroom(800,800,2000);
    
	cmpc(0);
	while(gmpc(0)<2200)
	{
    	Vroom(2000,0,0);
    	msleep(500);
    	Vroom(0,2000,0);
    	msleep(500);
	}
    
    
	
	printf("Task 2 over\n");
    Vroom(-800,0,2900);
   	Vroom(800,800,5400);
    Vroom(800,0,2900);
    Vroom(-500,-500,2300);
    Vroom(-800,0,2900);
    Vroom(-500,-500,2500);
    Vroom(500,500,2500);
    Vroom(-800,0,2800);
    Vroom(-500,-500,1100);
    Vroom(0,-800,2800);
    Vroom(-500,-500,2500);
    Vroom(500,500,2500);
    Vroom(-800,0,2800);
	printf("Pushed first set\n");
    
	Vroom(-800,-800,4000);
	Vroom(500,500,3000);
	Vroom(0,800,2900);
	Vroom(500,500,2000);
	Vroom(-500,-500,2000);

	Vroom(0,-800,1900);
	Vroom(-800,0,2000);
	Vroom(800,800,3000);
	printf("Second pair pushed\n");
	Vroom(-800,-800,3200);
	printf("Task 1 completed\n");

	//Task 3 commence
	printf("Task number 3/n");
	Vroom(0,800,2900);
    Vroom(800,800,5000);
    Vroom(800,0,2900);
    Vroom(1000,1000,2600);
	Slapper(0,836);
	Vroom(0,800,2900);
	//Make sure to angle the robot exactly so it can push the objects effictevely, don't go too fast 
	Vroom(500,500,5000);
	Vroom(1000,1000,3000);
	Vroom(0,800,2900);
	Vroom(500,500,2500);
	Vroom(800,0,2900);
	Vroom(1000,1000,2500);
	//Aprox.(117.5)
	return 0;
}//End int
