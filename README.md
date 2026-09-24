## Описание
Развернул Foreman на локальной Ubuntu 24.04 машинке  

Создал managed хост
<img width="3068" height="1936" alt="image" src="https://github.com/user-attachments/assets/5df8ca21-17c2-4b69-9db9-00f24eb1e229" />

Создал Host Group с базовым provisioning template с донастройкой NTP
<img width="3068" height="1936" alt="image" src="https://github.com/user-attachments/assets/b229c41c-1493-44b3-ae9b-5e5fb6cbe5a1" />
<img width="3068" height="1936" alt="image" src="https://github.com/user-attachments/assets/91f70c6a-4973-45c1-a42b-abe8fc1a9ba3" />
<img width="3068" height="1936" alt="image" src="https://github.com/user-attachments/assets/15e0dbe9-4da2-48ec-85a7-52973cbe730a" />

Написал ansible роль по запрету входа рута, импортировал в foreman и применил к ранее созданной группе хостов
<img width="3068" height="1936" alt="image" src="https://github.com/user-attachments/assets/4c45ab1e-8016-4c22-a517-47bf0f79e0b9" /> 
