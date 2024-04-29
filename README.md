# CS-350-Emerging-Sys-Arch-and-Tech

__Summarize the project and what problem it was solving.__
<br/>
<H6>
  In the final project, I developed code that initialized a timer, intterupts to detect button presses, an I2C peripheral to read a temperature sensor, a GPIO peripheral to control the LED, and a UART peripherla to output data to the server. There is a setPoint with a specified temperature, in this case it is 20, the buttons on the microcontroller control the setPoint (increase and decrease). If the temperature is lower than the setPoint the LED turns on to heat the temperature, but if the temperature is lower than the setPoint the LED turns off to "cool" the sensor.
</H6>
<br/>

__What did you do particularly well?__
<br/>
<H6>
  I did well at converting the given UART function and variables to UART2. It was a bit tough at first since the functions and variables given in the lab guide were outdated, but after some research I managed to complete and correct the UART portion of the project.
</H6>
<br/>

__Where could you improve?__
<br/>
<H6>
  The code is very long and unorganized, I think I could do better at writing shorter more efficient code and keeping my code organized.
</H6>
<br/>

__What tools and/or resources are you adding to your support network?__
<br/>
<H6>
  On the TI website I found a "UART2.h File Reference" page that made it much easier to convert from UART to UART2, here is a link: https://software-dl.ti.com/simplelink/esd/simplelink_cc13x2_26x2_sdk/4.20.00.35/exports/docs/tidrivers/doxygen/html/_u_a_r_t2_8h.html
  <br/>
  I will be using this in future projects where I need to convert from UART to UART2.
</H6>
<br/>

__What skills from this project will be particularly transferable to other projects and/or course work?__
<br/>
<H6>
  Reading the header files thouroughly was really helpful, I've never had to read so much into header files in order to understand. Being able to read and understand the header files will help me in many projects and future course work.
</H6>
<br/>

__How did you make this project maintainable, readable, and adaptable?__
<br/>
<H6>
  I made sure to include comments in the code that are easy to follow and understand, and I updated the code from UART to UART2. This will help me reuse this code in future projects where UART or UART2 is used.
</H6>
