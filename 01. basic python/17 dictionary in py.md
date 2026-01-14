```python
my_dict = {'name': 'Alice', 'age': 25, 'city': 'New York'}
keys = my_dict.keys()  # returns dict_keys view
keys_list = list(keys)  # converts keys to a list
print(keys_list)  # Output: ['name', 'age', 'city']



capitals = {
"name":"yuvraj",
"age":"20",
"skills":"python"
}

print(capitals["name"])
print(capitals.get("name"))



  

capitals['name'] = "raju"
print(capitals)
capitals.update({'name':"lagan"})
student1["address"]="xyz"
print(capitals)

capitals.pop("skills")
# this via target

capitals.popitem()
# this remove the latest


a =capitals.keys()
for key in capitals.keys():
	print(capitals[key])


a =capitals.values()
print(a)


print(capitals.items())
# this gives a 2d list of tupples


for keys,value in capitals.items():
	print(f'{keys} : {value}')


```



```python
for key in my_dict:
    print(key)
    
keys_list = [key for key in my_dict]

```

