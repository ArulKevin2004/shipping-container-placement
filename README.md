# **Convex Hull and Container Placement Visualization**

## **Overview**
This project demonstrates the use of the Graham Scan algorithm to find the convex hull of a given set of container positions in a 2D plane. The convex hull is visualized in ASCII art to show which containers form the boundary of the placement.

---

## **Features**
1. **Input Points**: Allows the user to input container positions.
2. **Convex Hull Calculation**: Computes the convex hull using the Graham Scan algorithm.
3. **Visualization**: Generates an ASCII art representation of the container layout and the convex hull.
4. **Orientation Checks**: Determines the turn type (clockwise, counterclockwise, or collinear) for three points.

---

## **How to Run**
1. Compile the program using a C++ compiler:
    `g++ scp.cpp -std=c++11 -o scp`
2. Run the program:
   `./scp`
3. Input Data:
   - Enter the number of containers.
   - Enter the Cartesian coordinates (x y) for each container.
4. Output:
   - List of container positions.
   - Points forming the convex hull.
   - ASCII visualization of container placement and the convex hull.
## Sample input
```bash
Enter the number of containers: 5
Enter the container positions (x y):
1 5
2 3
3 7
4 8
5 10

```
## Sample output
```bash
Container Positions:
(2, 3)
(5, 10)
(4, 8)
(3, 7)
(1, 5)
Convex Hull Points:
(2, 3)
(5, 10)
(1, 5)
.*...
.....
*....
.....
..C..
...C.
.....
....*

```

