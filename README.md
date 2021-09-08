## Test Plan

## High Level Test Plan

| Test ID | Description | Exp I/P | Exp O/P |	Actual Output | Type of Test |
| --- | --- | --- | --- | --- | --- |
| T_01 | Check if the code is working as expected, by considering the test cases | Inster movie | Movie is inserted | movie is insterted | Unit testing |
| T_02 | Verify whether view all movies is showing the movies that are inseted  |  Viewing the movies those are inserted| The inserted movies should be shown in All movies | The inserted movies should be shown in All movies | Integration Based |
| T_03 | Verify whether the book tickets is working  | The input should given by the user according to the fields | The ticket should be booked  | The ticket should be booked | | Integration Based |
| T_04 | verify wheter veiw all transactions  | The  booked showed be visible | The transactions should be visible | The transactions should be visible | Integration Based |
| T_05| Verify the exit field| The booking will be ended | The booking system should end | The booking system should end | Integration Based |




## Low Level Test Plan 

| Test ID | Function name | Description | Type of Test | Status (PASS/FAIL) |
| --- | --- | --- | --- |  --- |
| TL_01 | Insert movie | checks if the given name, movie code ,Release date ,Ticket price , value are valid or not | unit test | PASS |
| TL_02 | View All Movies | checks if the given movie name ,movie code ,Release date ,Ticket price  valid or not  | unit test | PASS |
| TL_03 | Book Tickets | checks if the given movie code, details like name, number and number tickets,total seats , cost per head is valid or not | boolean | unit test | PASS |
| TL_04 | View all transactions | Check if the given information is showing or not | unit test | PASS |
| TL_05 | Exit | Check when we click on exit the commands closes  | unit test | PASS |



## Exit Test Case output

![Screenshot (329)](https://user-images.githubusercontent.com/58597785/132361550-4fd106cf-5613-4172-b9f9-96b207ad43b9.png)


