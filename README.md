# SRAM Layout Project
Originally a school assignment. It required an SRAM layout and circuit files used to optimize bitlines and transistors (only for all the other supporting componenets because SRAM transistor size was a constraint) for maximum performance and minimal space occupied. Used a 50nm CMOS model from CMOSedu.com.

# SRAM cell layout image
![Screenshot from 2022-06-02 00-49-21](https://user-images.githubusercontent.com/101908514/171586519-41f4d23d-ee53-4e93-a8c8-66c029839168.png)
Constraints: only metal 1 and 2 were allowed for the design of the SRAM cell along with connections to VDD, GND, and write lines. Metal 3 was for the bitlines and of course N-well and P-well connections had to be included and connected to the appropriate VDD and GND lines. The transistors also had to be 5x2 lambda.

The test circuit files are for testing the different componenets of the SRAM module where I had to optimize size for these different componenets and dummy loads were used to simulate the capacitive and resistive load that would normally be there without actually having to implement them to save time on the project. Ultimatly due to time constraints a mojority of the work was done on optimizing SRAM bitline widths and SRAM layout including the design of how the cells would be placed (1x256, 2x128, 4x64, 8x32 or 16x16) which of course  had an effect on how thin of a bitline you could get away with while maintaining good reads and writes.
