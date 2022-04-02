# Challenge 1 : BlinkIt
---

## 1.Objective
Blink 8 leds using 8 GPIO pins of an arduino.
## 2. How To
Connecting the pins from 2 to 9 of arduino uno to 8 leds which are grounded to the GND pin of arduino using a 300 ohm resistor.
Running the below code gives us the result:

`
void setup()
{
for(int i = 2;i <= 9;i++){pinMode(i, OUTPUT);}
}
void loop()
{
    for(int i = 2;i <= 9;i++)
    {
        digitalWrite(i, HIGH);
        delay(1000);
        digitalWrite(i, LOW);
        delay(1000);
    }
}
`
Designs : [TinkerCAD Designs](https://www.tinkercad.com/things/kms4PxPE7Uj-amazing-vihelmo-luulia/editel?sharecode=lrs1CmjeAUGR9lk9PYUFVNm8D3uNxDBrbQqNwdrtUdk)

## 3.Result
The result would be : 
![Final Result](https://user-images.githubusercontent.com/73999623/161377416-af2a3142-172c-49ee-8485-a36c3d7765ce.gif)