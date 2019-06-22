# ADC-Distance-Measurement
Use SysTick interrupts to periodically initiate a software- triggered ADC conversion, convert the sample to a fixed- // point decimal distance, and store the result in a mailbox. // The foreground thread takes the result from the mailbox,  converts the result to a string, and prints it to the  Nokia5110 LCD.  The display is optional.
