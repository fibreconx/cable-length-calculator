# cable-length-calculator


The equation is below:

![equation](./equation.svg)


The variables elements is as follows:
- Conduit Distance [Calculated Conduit distance] = Variable (required) (must be entered) 
- X(Ringbark) [No. Of ringbarks being installed]= Variable (Optional) (must be an integer/whole number, default = 0)
- X(A-End) [Amount of cable being left at end of haul]= Variable (Optional) (must be an integer/whole number, default = 20 if empty, unless there is DC ISP hauling then they need to enter the distance)
- X(Z-End)  [Amount of cable being left at end of haul] = Variable (Optional) (must be an integer/whole number, default = 20 if empty, unless there is DC ISP hauling then they need to enter the distance)
- Y(Allowance) [Percentage of additional cable to be added] = Variable (required) (must be entered as an integer/whole number)
- Y(Allowance) is a percentage of additional cable and is actual represented as `1.[Y(allowance)]`
  - Example 1: Y(Allowance) = 4, is represented as 1.04
  - Example 2: Y(Allowance) = 25, is represented as 1.25

Also to note with the above equation, the `[Conduit Dist/500]` needs to be rounded up the next integer/whole number.
