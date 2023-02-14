		Airbnb clone

First phase of building a full web application "The AirBnB"

The project is linked in the following ways:
	put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances
	create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
	create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
	create the first abstracted storage engine of the project: File storage.
	create all unittests to validate all our classes and storage engine

In this project, we want to manage the following objects:
	Create a new object (ex: a new User or a new Place)
	Retrieve an object from a file, a database etc…
	Do operations on objects (count, compute stats, etc…)
	Update attributes of an object
	Destroy an object


