# Skills

## My skills
1. Football
1. Ping-Pong
1. Billards
1. Frisbee
1. Cornhole

## Characteristic Skills
1. Great leader, I was a captain of my football team.
1. Responsibile

## Code Skills!
def main():
    # take input for choice
    print("1. Volume of a cone");
    print("2. Volume of a cylinder");
    print("3. Volume of a cube");
    choice = int(input("Enter your choice: "));
    if choice == 1:
        #calculate volume for cone
        r = int(input("Enter radius of cone: "));
        h = int(input("Enter height of conne: "));
        # Volume = (1/3) * pi * r^2 * h
        print("Volume of cone: ", 0.33 * 3.14* r * r * h);
    elif choice == 2:
        #calculate Volume for cylinder
        r = int(input("Enter radius of cylinder: "));
        h = int(input("Enter height of cylinder: "));
        # Volume = pi * r^2 * h
        print("Volume of cone : ", 3.14 * r * r * h);
    elif choice == 3:
        #calculate volume for cube
        a = int(input("Enter a side of the cube: "));
        # Volume =a^3
        print("Volume of a cone: ", a * a * a);
    else:
        #error message
        print("Error");
# call main function
main();

[Go back to home page](./README.md)