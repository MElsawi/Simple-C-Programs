# Simple-C-Programs
====================

Simple C text game. 



#include <stdio.h>
int main(void)
{
    
    
    int num;
 
    printf("\n\nWelcome to the maze of destruction, beware of the choices you make.\n");
    printf("\nTo enter the maze press 1\n");
    scanf("%d" , &num);
    if(num == 1) 
        printf("\n\nYou've made a brave choice, but a dangerous one, there's no turning back now.\n");
 
    if (num != 1) 
    {
        printf("Well adventurer, it would seem that you've made a wise choice to back down.\n");
 
    return 0;
    }
 
 
    printf("\nYou come accross a body that seems to be unconcious, what now adventurer?\n\n");
    printf("[1] Leave the body alone.\n");
    printf("[2] Reach through the pockets to find anything that could be of use.\n");
    scanf("%d" , &num);

    if (num == 1)
    {
        printf("\n\nYou keep moving forward through the maze until you start to realize that you\n");
        printf("we're swallowed by the darkness inside the maze.\n");
    }
    else 
    {
        printf("As you kneel down to look through the pockets, you begin to realize a slow\n");
        printf("movement as if the body hadn't fully tasted death just yet, a hand suddenly\n");
        printf("grasps onto your neck as you attempt to breathe for your life, then you fall\n");
        printf("to the ground motionless to your death.\n");
 
    return 0;
    } 
 
    printf("You can't see a soul, but you feel as if you we're being watched this entire time.\n");
    printf("[1] Flee as fast as you can, there's no telling what that creature is.\n");
    printf("[2] Running won't help at this moment, best to just fall to the ground and accept your fate.\n"); 
    scanf("%d" , &num);
 
    if (num == 1) 
    {
        printf("\n\nA growl starts to echo throughout the maze, you can feel as a great beast was gaining on to you\n");
    }
 
    else 
    {
    printf("\n\nThe beast instantly accepts your surrender and rips you appart with its claws.\n");
 
    return 0;
    }

    printf("A source of light is in the distance! You pace with every last breath to reach the end of the maze\n\n");
    printf("[1] Keep running, don't even think about stopping, you can feel it breathing down your neck!\n");
    printf("[2] You turn to the creature and attemt to get ahold of it.\n"); 
    scanf("%d" , &num);

    if (num == 1)
    {
    printf("\n\nYou blaze outside the maze, luckily unharmed. The daylight is brighter you've ever seen.\n\n");
    }
    else 
    {
    printf("A growl soars throughout the maze, you can't see a thing. You feel the creature as come toward you.\n");
    printf("but can't exactly tell from which direction since you're in pure darkness. When all goes silent, you\n");
    printf("begin to wonder what had happened, but just before you sigh in relief, the beast knocks you down with\n");
    printf("its mighty claw\n\n");
    return 0;
    } 

    printf("You've made it through the maze, unfortunately, the same can't be said about most other adventurers.\n");
    return 0;
    }
