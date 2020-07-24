
## Java 

Data types

byte

short

int

long

float

double

boolean

char

**Arrays**

Fixed size, access by index key


**Java ArrayList**
A resizable array, dynamic size, access element by index number

```
    ArrayList<String> cars = new ArrayList<String>();
    cars.add("Volvo");
    cars.add("BMW");
    cars.add("Ford");
    cars.add("Mazda");
    System.out.println(cars);
```

**Java LinkedList**
* A collection class which can contain many objects of the same type
* Almost identical to Java ArrayList
* ArrayList and LinkedList can be used in the same way, but built very differently

**Java HashMap**

* A HashMap class stores items in key/value pairs
* Can be accessed using index of another type e.g. a string
* 

Example:

Create a HashMap object called capitalCities

```
    HashMap<String, String> capitalCities = new HashMap<String, String>();
    // Add keys and values (Country, City)
    capitalCities.put("England", "London");
    capitalCities.put("Germany", "Berlin");
    capitalCities.put("Norway", "Oslo");
    capitalCities.put("USA", "Washington DC");
    System.out.println(capitalCities);
```
