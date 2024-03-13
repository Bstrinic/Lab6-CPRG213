LAB 6 CPRG - 211 - F

Instructions
1. Using C# IDE, create a class called Event that has two properties:
• event number
• location

2. Create an object from the class and assign a value of 1 to the event number property and a
value of Calgary to the location property.

3. Use serialization to serialize the object to a file called event.txt.

4. Use deserialization to deserialize the object from the file and display the values on the
Console.

5. Create a list of 4 Event objects (event number and location of your choice) and serialize it
into a json file. Deserialize the json file into event object and display the values on the
Console

6. Create a method called ReadFromFile, where you write the word “Hackathon” to the file,
and then read the first, middle and last characters using StreamWriter and the Seek
method.

Expected Output
1
Calgary
Tech Competition
In Word: Hackathon
The First Character is: "H"
The Middle Character is: "a"
The Last Character is: "n"
