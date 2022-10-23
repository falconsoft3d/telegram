# telegram


```
1- Find the contact "BotFather"
2- Send /newbot to create a new Telegram bot.
3- Yo have new Token like : DEMO:AAEIr7H7l_ukqgE2ktSrW5F2a2SdU2whxIs
4- Create a Group
5- Add this bot <Telegram Bot Raw> for know the id of the group
6- /start
7- pip3 install telebot
```


```
import requests
import json

url = "https://api.telegram.org/bot5778116097:AAEIr7H7lDEMOxIs/sendMessage"

payload = json.dumps({
  "text": "1",
  "chat_id": "-8611139222"
})
headers = {
  'Content-Type': 'application/json'
}
response = requests.request("GET", url, headers=headers, data=payload)
print(response.text)
```
