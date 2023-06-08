# Differential Amplifier
## Abstract 
### A differential amplifier is a fundamental building block in analog VLSI (Very Large Scale Integration) circuits. It is commonly used to amplify the voltage difference between two input signals while rejecting common-mode noise.
## Implimentation 
 To  generate high voltage gain ,we need to use cascode combination of common source amplifier cicuits that with same input voltage at two input side with opposite phase 
   I have used ** cadence virtuoso **
   Generation and calculation of size of Differential amplifier
 
 1.Decide the length of technology ,as i have 180nm technology file in my college Cadence lab  
 
 2.Decide Cc(Compensation capacitor) Cc>= 0.22*Cl
 
 3. Decide Currenet in current mirror circuit using Slew rate(SR=(I5/Cc)) and given power(Power/Vdd) .Whichever current minimum in between will be taken in our calculation for    minimum power optemization
4. Find The size of M1 and M2 (depends on Gain Bandwidth and Cc)
5. Finds the size of M3 and M4 
6. Finds the size of M5
 ## Schematic
 ![Differential Amplifier](https://github.com/mec2021045/Two-Stage-Differential-Amplifier/assets/115482179/c3936a0e-6255-4a23-b402-067dccfa6081)

## Analysis

## Result

### 
Transient analysis
![Transient Analysys](https://github.com/mec2021045/Two-Stage-Differential-Amplifier/assets/115482179/2912a48b-c5aa-4f7a-b3e1-d380f3b6eebe)The Temperature coeffiecient is Verf is calculted from maximum and minimu voltgae generated by Vref Curve and found out be 11 ppm/degree celcuis .
![Transient Analysys1](https://github.com/mec2021045/Two-Stage-Differential-Amplifier/assets/115482179/090539f7-1820-447b-b302-15eb33b10a32)
AC Analysis 
![AC Analysis](https://github.com/mec2021045/Two-Stage-Differential-Amplifier/assets/115482179/b9f9ae2c-9731-4105-bc82-bdefb45baa65)
Finally i got 30db gain 
## Author
### Raju Kumar Yadav (IIIT Allahabad)
