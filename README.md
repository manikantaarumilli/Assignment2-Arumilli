# Assignment2-Arumilli


# Manikanta Arumilli
###### Bheemavaram  Restaurant
We do have Mall named **Geetha multiplex** right beside it and A movie theatre  called **NATARAJ**to the left of it.



---

### Directions to reach the food place

Vijayawada international airport

1. Look for the cab after you come out of the airport.
2. The distance from airport to the Restaurant is almost 120miles, it takes 2hours to reach the         destination.
3. Will find the Restaurant  on the  Main road,  geetha multiplex is right side to it.


### I recommend others to taste the below items
 
   * vegetarian
     
     * paneer
     * Mushroom
     * veg pulao
    
   * Non-vegetarain
    
      * Bheemavaram Chicken biryani
      * Mixed non-veg
      * Prawns
      * Crab

      [Link to AboutMe](AboutMe.md)




---

# Sports Table

 The following table represents the Sports Activities that someone can lookup on their interest.

|Sport|Location|Cost|    
|---|---|---|
|Cricket|Australia|110$|
|Badminton|USA|1k$|
|Tennis|india|60$|
|Football|UK|90$|


---

# Pithy Quotes

> "Looking Good Is The Best Revenge" - *Ivana Trump*

> "The Purpose Of Our Lives Is To Be Happy" - *Parade*


---

# code fencing

> Orientation of an ordered triplet of points in the plane can be
  counterclockwise
  clockwise
  collinear

Link to source <https://www.geeksforgeeks.org/orientation-3-ordered-points/?ref=gcse>

```
int signed_area_parallelogram(point2d p1, point2d p2, point2d p3) {
    return cross(p2 - p1, p3 - p2);
}

double triangle_area(point2d p1, point2d p2, point2d p3) {
    return abs(signed_area_parallelogram(p1, p2, p3)) / 2.0;
}

bool clockwise(point2d p1, point2d p2, point2d p3) {
    return signed_area_parallelogram(p1, p2, p3) < 0;
}

bool counter_clockwise(point2d p1, point2d p2, point2d p3) {
    return signed_area_parallelogram(p1, p2, p3) > 0;
}

```

Link to source code <https://cp-algorithms.com/geometry/oriented-triangle-area.html>






