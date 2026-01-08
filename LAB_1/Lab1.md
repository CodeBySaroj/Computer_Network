# Lab 1: Connecting Network Devices Using Ethernet

## Preparation of Ethernet Cable with RJ45 Connectors

## Materials Required
- Ethernet cable (Cat5e or Cat6)
- RJ45 connectors
- Crimping tool
- Wire stripper
- Cable tester


## Procedure

### Type 1: Straight-Through Cable

1. Cut the Ethernet cable according to the required length.  
2. Remove approximately 1 inch of the outer insulation from both ends of the cable using a wire stripper.  
3. Untwist and arrange the wires following the **T568B wiring standard**:
   - Pin 1: White/Orange  
   - Pin 2: Orange  
   - Pin 3: White/Green  
   - Pin 4: Blue  
   - Pin 5: White/Blue  
   - Pin 6: Green  
   - Pin 7: White/Brown  
   - Pin 8: Brown  
4. Trim the wires evenly so they are of the same length.  
5. Insert the wires into the RJ45 connector, ensuring each wire is in the correct slot.  
6. Crimp the connector securely using a crimping tool.  
7. Repeat the same process for the other end of the cable.  
8. Test the cable using a cable tester to verify proper connectivity.

### Type 2: Crossover Cable

1. Follow steps 1–4 from the straight-through cable procedure.  
2. Arrange one end of the cable using the **T568A wiring standard**:
   - Pin 1: White/Green  
   - Pin 2: Green  
   - Pin 3: White/Orange  
   - Pin 4: Blue  
   - Pin 5: White/Blue  
   - Pin 6: Orange  
   - Pin 7: White/Brown  
   - Pin 8: Brown  
3. Arrange the other end using the **T568B wiring standard**:
   - Pin 1: White/Orange  
   - Pin 2: Orange  
   - Pin 3: White/Green  
   - Pin 4: Blue  
   - Pin 5: White/Blue  
   - Pin 6: Green  
   - Pin 7: White/Brown  
   - Pin 8: Brown  
4. Trim all wires to equal length.  
5. Insert the wires into the RJ45 connectors carefully.  
6. Crimp both connectors properly using the crimping tool.  
7. Test the crossover cable using a cable tester.

## Connection Testing Using Cable Tester

1. Connect one end of the cable to the transmitter unit of the cable tester.  
2. Connect the other end to the receiver unit.  
3. Power on the tester and observe the results:
   - **Straight-through cable:** Pins light up in the same order from 1 to 8.  
   - **Crossover cable:** Transmit and receive pairs are crossed  
     - Order: `1-3, 2-6, 3-1, 6-2`


## Results
- The cable tester confirmed that all wire connections were correct with no faults.
- Both straight-through and crossover cables functioned as expected.


## Conclusion
In this lab, we successfully prepared and tested both straight-through and crossover Ethernet cables. By carefully following the wiring standards and verifying the connections using a cable tester, reliable network communication was achieved. This experiment improved our practical understanding of Ethernet cabling and its importance in building stable computer networks.
