## -Create-a-new-dictionary-by-extracting-the-following-keys-from-a-given-dictionary-Given-dictionary-
## Sample code to check given dictonary
```sh
sampleDict = { 
  "name": "Kelly",
  "age":25, 
  "salary": 8000, 
  "city": "New york" }

keys = ["name", "salary"]

newDict = {k: sampleDict[k] for k in keys}
print(newDict)
```
## Expected output
{'name': 'Kelly', 'salary': 8000}
