# Parking Lot Design - 
    
### Requirements - 
**Functional Requirements**

    1. Multi Floor Parking-Lot
    2. Single Gate of entry
    3. Support of multiple Vehicle
        i. Car Size: 2
        ii. Bike Size: 1
        iii. Bus Size: 3
    4. Should support multiple payment options
        i. Card Payment
        ii. Cash Payment
    5. The system should not allow more vehicles than the maximum capacity of the parking lot
    6. Per hour parking charge model
                
                
**Non Functional Requirements**

    1. Low latency
    2. Dynamic balancing of spots
    3. Let's say the spots for cars have been finished and the spots for the bus are available, the system should dynamically convert a few Bus spots into Cars.
    4. Code should be extensible to add further features.
    
**Optional/Bonus**

    1. Support for multiple gates.
    2. Need to handle concurrency cases.
    3. Admin access
    4. Unit tests
    5. Multiple Algorithm implementation support, Algorithm for parking strategy should be optimal and configurable