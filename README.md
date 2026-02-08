#Aim :- To study and implement Python dictionaries for storing data in key–value pairs and to perform basic operations such as creation, accessing values, updating, deleting elements, and solving simple problems using dictionaries.

#Theory

A dictionary in Python is a mutable and unordered data structure used to store data in the form of key–value pairs.

Each key must be unique and immutable, while values can be of any data type.

Dictionaries are defined using curly braces {}. Syntax: dict_name = {key1: value1, key2: value2}

Dictionary values are accessed using their corresponding keys. Syntax: dict_name[key]

To avoid errors when a key is not present, the get() method is used. Syntax: dict_name.get(key, default_value)

Dictionaries allow updating existing values and adding new key–value pairs. Syntax: dict_name[key] = new_value

Elements can be removed from a dictionary using the pop() method. Syntax: dict_name.pop(key)

Built-in dictionary methods like keys(), values(), and items() are used to retrieve all keys, values, and key–value pairs respectively.

The max() function along with the get() method can be used to find the key having the highest value. Syntax: max(dict_name, key=dict_name.get)

#Algorithm

Start
Create a dictionary using {key: value}
Display the dictionary using print(dict)
Access required values using dict[key]
Add or update elements using dict[key] = value
Remove elements using dict.pop(key)
Safely retrieve values using dict.get(key, default)
Process dictionary data using max(dict, key=dict.get)
Display the final output
Stop
#Conclusion

Thus, the experiment was successfully performed and the concept of Python dictionaries was studied. Operations such as creation, accessing, updating, deletion, and processing of dictionary data using built-in methods and functions were implemented effectively
