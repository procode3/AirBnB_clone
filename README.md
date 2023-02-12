## Airbnb clone

The 1st version of the AirBnb clone has a basemodel that handles three instance variable id, created_at and updated_at. All the other model classes inherit from the basemodel.

# DB
The curent database is a json file that stores serialized data.

# Engine
The engine that handles serialization, the FileStorage class uses json dump and json load to write and read the file

# Console
The console is used to test the creation and serialization of files in a CLI.

## Running the console
In the root folder run
```bash
$ ./console
```

## Testing models
# Creating a BaseModel instance

```bash
(hbnb) create BaseModel
```
# Creating a new user instance

```bash
(hbnb) create User
```
# Displaying all user instances

```bash
(hbnb) all User
```
# Display a specific instance
```bash
(hbnb) show User f4f30cb6-2551-4c4b-99dd-cd59d1ebe32b
```

## Contributing

Pull requests are welcome. Reach out for major changes. 

Please ensure you update tests as appropriate

## License
[ALX](https://www.alxafrica.com/)
