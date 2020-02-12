# Request_Python

# get request 
import requests 
URL = "http://192.168.50.93:8001/Restaurant/" 
r = requests.get(url = URL)  
data = r.json()
for x in data :
    for y in x :
        print(y, x[y])
