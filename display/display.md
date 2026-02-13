## Display

For the display of my calculator, I used a 7-segment display. Specifically, I used a **common-anode** display.

My idea behind this is to display BCD numbers. Once my output is generated, it will be converted to BCD, and this will be displayed on 7-segment displays ,for the time being.

Later, I want to upgrade this to display on a screen.

I used a common display driver or decoder, the **74HC47**.

<img width="975" height="483" alt="image" src="https://github.com/user-attachments/assets/38425b25-d95f-4e16-9930-f5511ae717b5" />


This is a Multisim model of what I was talking about. The Multisim design file is included in this directory 


I also implemented this on a breadboard.
<img width="975" height="552" alt="image" src="https://github.com/user-attachments/assets/c4e93a8d-8e87-4505-9c00-4b8bf73f9461" />

The least significant bit corresponds to **DIP switch 5**, and the most significant bit corresponds to **DIP switch 8**. Please note that **“ON”** on the switch is actually **“off”** (sorry for the confusion).

With switches **5 and 8 ON**, a signal of **1010** should be transmitted, and the circuit displays a **5** as expected.


