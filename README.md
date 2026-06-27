# Musical Instrument Inventory

A simple Python program designed to demonstrate the basics of **Object-Oriented Programming (OOP)** by managing a collection of musical instruments.

## Description
This program defines a `MusicalInstrument` class that stores information about instruments, including their name and family type. It includes methods to display a fun message about playing the instrument and to retrieve a descriptive fact about the instrument's classification.

## Features
* **Class Structure**: Defines a blueprint for `MusicalInstrument` objects.
* **Initialization**: Assigns unique attributes (`name`, `instrument_type`) to every instance created.
* **Methods**:
    * `play()`: Prints a message to the console.
    * `get_fact()`: Returns a formatted string with details about the instrument's family.

## Example Usage
```python
# Create an instance
instrument_1 = MusicalInstrument('Oboe', 'woodwind')

# Call the methods
instrument_1.play() 
# Output: The Oboe is fun to play!

print(instrument_1.get_fact()) 
# Output: The Oboe is part of the woodwind family of instruments.
