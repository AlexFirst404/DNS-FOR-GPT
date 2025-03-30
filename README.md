# DNS-FOR-GPT
Обход блокировки для chat gpt (openai) актуальный способ на 30.03.2025 (FOR LINUX)

### LINUX
Выполняем DNS-запрос к comss (подставил актуальный на момент написания адрес):
В терминале вводим:
```
nslookup chatgpt.com 83.220.169.155
```

Ответ должен быть примерно таким:

![image](https://github.com/user-attachments/assets/285ef830-ee24-497b-b33b-89d179c7ae42)

далее добавляем в файл hosts строки:
```
sudo nano /etc/hosts
```
```
94.131.119.85 chatgpt.com
94.131.119.85 auth.openai.com
94.131.119.85 chat.openai.com
94.131.119.85 ab.chatgpt.com
94.131.119.85 cdn.oaistatic.com
94.131.119.85 webrtc.chatgpt.com
```
Возможно для применения и работы способа придется перезагрузить устройство
