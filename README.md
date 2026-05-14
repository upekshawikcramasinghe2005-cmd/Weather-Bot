# Weather-Bot
print('Input your city and find your weather')
input=('Enter your city name: ')
url = f"http://wttr.in/{city}?format=3"
response=requests.get(url)
print(response)
