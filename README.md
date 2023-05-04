# CarRaceSimulation



### CarRaceSimulation 🚗 
is a console application that simulates a car race between two cars. Each car has a speed and a starting position, and the application simulates how long each car takes to reach the finish line.

During the race, random events can affect both cars' speed and time. For example, a car may need to stop to refuel or change tires, or lose time due to technical problems.

## Running the Program

The program can be run by opening the project in a C# IDE like Visual Studio and running Program.cs. 
When the program is run, the following messages are displayed in the console:

Welcome To Grand Prix Monaco 🏁

Press any key to start

When the user presses a key, the race starts and all the third cars begin moving towards the finish line.
While the race is in progress, the console is updated with information about each car and events that affect their performance.

When the race is over, the following message is displayed in the console:

Race Done

## Codebase

The codebase is written in C# and consists of three methods:


```sh
Main: The main method that runs when the program starts. It creates two cars and then runs the RunRace method for each car.
RunRace: Simulates the race for a single car. The method takes two parameters: a CarModelClass that represents the car and a racelength that represents the length of the track in kilometers.
RaceStatus: Updates the console with information about both cars and their progress during the race.
```

The codebase also includes a CarModelClass class that defines the properties of a car.
