# GOOGLE-Wall-Following-
AIM

To implement a wall-following control strategy based on distance error.

PROCEDURE
Initialize desired distance and actual distance from the wall
Compare actual distance with desired distance
If actual < desired, move away from the wall
Otherwise, maintain or move closer if needed
Display the control action
CODE
# Input values
desired = 0.5   # in meters
actual = 0.2    # in meters

# Wall-following logic
if actual < desired:
    action = "Move Away from Wall"
else:
    action = "Maintain Distance"

# Output
print(action)
OUTPUT

Move Away from Wall

RESULT

The robot correctly moves away from the wall when it is too close, maintaining a safe distance during navigation.
