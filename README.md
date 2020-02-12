# Request_Python

# get request 
```
import requests 
URL = "votre url" 
r = requests.get(url = URL)  
data = r.json()
for x in data :
    for y in x :
        print(y, x[y])
```
