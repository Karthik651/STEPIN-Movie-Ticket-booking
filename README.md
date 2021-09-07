## Test Plan

## High Level Test Plan

| Test ID | Description | Exp I/P | Exp O/P |	Actual Output | Type of Test |
| --- | --- | --- | --- | --- | --- |
| H_01 | Check if the code is working as expected, by considering the test cases | Jumbled cube | Solved Cube | Solved Cube | Scenario Based |
| H_02 | Check if the system handles boundary conditions | Invalid Cube | Error | Error | Boundary Based |
| H_03 | Check if cross is obtained in first layer | Jumbled Cube | Cross obtained | Cross obtained | Integration Based |
| H_04 | Check if first layer is solved| Solved Cross Cube | First layer solved cube | First layer solved cube | Integration Based |
| H_05 | Check if second layer is solved | First layer solved cube | Second layer solved cube | Second layer solved cube | Integration Based |
| H_06 | Check if top layer cross is obtained | Second layer solved cube | Top layer cross obtained | Top layer cross obtained | Integration Based |
| H_07 | Check if top layer edges are aligned | Top layer cross obtained cube| Top layer edges aligned | Top layer edges aligned | Integration Based |
| H_08 | Check if top layer corners are aligned | Top layer edges aligned cube | Top layer corners aligned | Top layer corners aligned | Integration Based |
| H_09 | Check if top layer is solved | Top layer corners aligned | Solved cube | Solved cube | Integration Based |



## Low Level Test Plan 

| Test ID | Function name | Description | Return type | Valid Input Range |	Output Range | Output for out of range/invalid inputs | Type of Test | Status (PASS/FAIL) |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L_01 | is_i_j_k_valid | checks if the given i,j,k value is valid or not | boolean | i,j,k value between 0 and 2 | 0 and 1 | 0 | unit test | PASS |
| L_02 | isIndexValid | checks if the given index is valid or not for a given i,j,k value| boolean | i,j,k,index value between 0 and 2 | 0 and 1| 0 | unit test | PASS |
| L_03 | isPositionValid | checks if the given position is valid or not | boolean | position value can be FRONT, BACK, UP, DOWN, LEFT, RIGHT | 0 and 1 | 0 | unit test | PASS |
| L_04 | getSize | returns size for given i,j,k values | int |  i,j,k value between 0 and 3 | 0 to 2 | -1 | unit test | PASS |
| L_05 | getPosition | returns position for given i,j,k,index values | string | i,j,k,index value between 0 and 2 | FRONT, UP, LEFT, RIGHT, BACK, DOWN  | NULL | unit test | PASS |
| L_06 | getLocation | returns location for given i,j,k values | int | i,j,k value between 0 and 2 | all possible locations of rubik's cube | NULL | unit test | PASS |
| L_07 | get_index | returns index value for given i,j,k,position values | int | i,j,k value between 0 and 2  | 0 to 2 | -1 | unit test | PASS |
| L_08 | isNodeValid | checks whether all the Nodes entered by the user is valid or not | boolean | N.A(colors from the user) | 0 and 1 | 0 | unit test | PASS |
| L_09 | isRubiksCubeValid | checks if the entered colors of rubiks cube have 6 colors where 9 are of same suit | boolean | N.A(colors from the user) | 0 and 1 | 0 | unit test | PASS |

## HIGH LEVEL TESTING RESULTS

![SolveSteps](https://github.com/GEN-AUG/SDLC_01_Falcon/blob/main/4_TestPlanAndOutput/SolveSteps.png)