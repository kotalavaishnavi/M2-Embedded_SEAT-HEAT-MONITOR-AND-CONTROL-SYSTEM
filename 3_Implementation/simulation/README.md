# Blinky Project In Action

|ON|OFF|
|:--:|:--:|
| 
![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/94221735/144048994-df05f206-2faf-4938-8f25-c9408d269504.gif)|

![Screenshot (45)](https://user-images.githubusercontent.com/94221735/144052026-a2a471fd-1edf-4e68-9775-a8bd643d3230.png)
## Code 
int main(void)
{
    uint16_t temp;
    
    while(1)
    {
        if(activity1_LED()==1) //Check if both the switches are pressed
        {
           
            TurnLED_ON();//Turn LED ON
            temp=activity2_GetADC(); //Get the ADC value
            activity3_PWM(temp); //PWM output based on temperature
		    activity4_USARTWrite(temp); //To Serial monitor to print Temperature
            

        }
        else  //in all other cases
        {
            TurnLED_OFF();//Turn LED OFF
		    _delay_ms(200);
        }

    }
    return 0;
}
