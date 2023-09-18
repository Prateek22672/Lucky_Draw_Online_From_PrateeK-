# Lucky_Draw_Online_From_PrateeK™
#include <stdio.h>
int main(){
    int n,gift,otp,addres;
    printf("WELCOME TO PRATEEK GIFT AREANA");
    printf("\n\nEnter your lucky number from 1 to 5 :");
    scanf("%d",&n);
    switch(n)
    {
        case 1:
        printf("Won Apple watch SE(Gen-2)");
        break;
        
        case 2:
        printf("Hurry Won iphone 13");
        break;
        
        case 3:
        printf("Won Apple watch SE(Gen-2)");
        break;
        
        case 4:
        printf("Won Apple watch SE(Gen-2)");
        break;
        
        case 5:
        printf("Won Apple watch SE(Gen-2)");
        break;
        
        default:
        printf("SORRY SOMETHING WENT WRONG\nPEASE TRY AGAIN");
        break;
    }
    printf("\n\nEnter phone number to reedem your GIFT:");
    scanf("%d",&gift);
    printf("Enter OTP:");
    scanf("%d",&otp);
    printf("Please enter your Address:");
    scanf("%d",&addres);
    printf("CONGRATULATIONS,\nGift Placed Delivery expected on 23-september,2023");
    return 0;
}
