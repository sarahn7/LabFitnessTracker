# LabFitnessTracker
This program reads the workout type, the duration, and the distance to calculate the amount of calories burned.
# How to Run
1. Open the program in your IDE
2. Enter workout name, duration and distance
3. View calculated calories output

# Example Output
Enter workout type: Night Run
Enter duration (minutes): 54
Enter distance (km): 7.8
--- Workout Summary ---
Workout: Night Run
Duration: 54 minutes
Distance: 7.8 km
Calories burned: 468.0

# Author
Sarah

# Code Explanation
```java
 double calories = distance * 60;
        System.out.println("Calories burned: " + calories);
// This code will calculate the calories burned and print it out
```
## Code Review
- **Reviewed by:** Victor O'Donnell
- **Status:** Checked code. Inheritance (`extends`), Scanner input, and calorie calculations are all correct and working!
