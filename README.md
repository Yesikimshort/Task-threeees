# Task-threeees
#include <kipr/botball.h>
#include "Alexandria.h"

int main()
{//Begin int
    printf("Hello World\n");
    Vroom(800,800,5200);
    Vroom(800,0,2900);
    Vroom(500,500,2100);
    Vroom(0,500,1500);
    Vroom(0,-500,1500);
    
    Vroom(-500,-500,1000);
   	Vroom(0,500,1500);
    Vroom(0,-500,1500);
    printf("Pushed first set\n");
    
    Vroom(-800,0,2800);
    Vroom(-800,-800,4000);
    Vroom(800,0,2800);
    Vroom(500,500,3000);
    Vroom(0,800,2800);
    Vroom(500,500,2000);
    Vroom(-500,-500,2000);
   	
    Vroom(0,-800,1900);
    Vroom(-800,0,2000);
    Vroom(800,800,3000);
    printf("Second pair pushed\n");
    Vroom(-800,-800,3200);
    printf("Task 1 completed\n")
    
    printf("Task 2 commence\n")
    Vroom(800,0,2900);
    Vroom(800,800,5200);
    //Slapper(close on pole);
    Vroom(500,500,1000);
    Vroom(-500,-500,2000);
    Slapper(1,1825);
    //Slapper(retract thing);
    
    Vroom(-100,-100,2000)
    Vroom(800,0,2900);
    Vroom(800,800,2600);
    
    Vroom(-800,0,2900);
    vroom(100,100,2000);
    //Slapper(close on pole);
    Vroom(500,500,1000);
    Vroom(-500,-500,2000);
    Slapper(1,1825);
    //Slapper(retract thing);
    
    Vroom(-800,-800,3000);
    Vroom(0,800,2900);
    Vroom(800,800,2600);
    Vroom(0,800,2900);
    Vroom(800,800,22000);
    
    cmpc(0);
    while(gmpc(0)<2200)
    {
        Vroom(2000,0,0);
        msleep(500);
        Vroom(0,2000,0);
        msleep(500);
    }
    printf("Task 2 over\n")
    
    //Task 3 commence
    printf("Task number 3/n");
    Vroom(-1000,-1000,2600);
    Slapper(3,836);
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
