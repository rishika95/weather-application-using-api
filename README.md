import requests
api_address = 'http://api.openweathermap.org/data/2.5/weather?q=chicago&appid=aed30fb49f0fc071dc7f6665efe99714'
json_data = requests.get(api_address).json()
print(json_data)




