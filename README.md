# AirBnB Clone - The Console
The Airbnb clone project for which we are creating a copy of the Airbnb. Only some features will be implemented and will be listed below once completed. At this stage, we are implementing an additional storage option. Based on which database is chosen (file storage or database storage), JSON is used or MySQL and SQLalchemy is used via Python. Fabric is used for application deployment.

#### Description of the command interpreter:
* Create a new object.
* Retrieve an object from a file, database, etc.
* Execute operation on objects. e.g. Count, compute statistics, etc.
* Update object's attributes.
* Destroy an object.

## Usage
To launch the console application in interactive mode simply run:

console.py

or to use the non-interactive mode run:

echo "your-command-goes-here" | ./console.py 


## File Descriptions
[console.py](console.py) - the console contains the entry point of the command interpreter. 
List of commands this console current supports:
* `EOF` - exits console 
* `quit` - exits console
* `<emptyline>` - overwrites default emptyline method and does nothing
* `create` - Creates a new instance of`BaseModel`, saves it (to the JSON file) and prints the id
* `destroy` - Deletes an instance based on the class name and id (save the change into the JSON file). 
* `show` - Prints the string representation of an instance based on the class name and id.
* `all` - Prints all string representation of all instances based or not on the class name. 
* `update` - Updates an instance based on the class name and id by adding or updating attribute (save the change into the JSON file). 

## Classes inherited from Base Model:
* [amenity.py](/models/amenity.py)
* [city.py](/models/city.py)
* [place.py](/models/place.py)
* [review.py](/models/review.py)
* [state.py](/models/state.py)
* [user.py](/models/user.py)

## Bugs
No known bugs at this time. 

## Authors
Afees Akinade - [Github](https://github.com/Afeezope) / [Twitter](https://twitter.com/AkinadeAfees)
