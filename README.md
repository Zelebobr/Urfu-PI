HEAD
## Urfu-PI 
# 1. Установка SSH-клиента и генерация ключевой пары
с помощью команды ssh-keygen -t ed25519 были сгенерированы 2 ключа и установлен пароль:

<img width="1157" height="648" alt="image" src="https://github.com/user-attachments/assets/4e547220-331a-4c2b-9edb-18c7c5e5f020" />

<img width="355" height="40" alt="image" src="https://github.com/user-attachments/assets/406b1856-85f3-4f2d-9dc5-eb22e134e70e" />

# 2. Добавление публичного ключа в аккаунт GitHub
публичный ключ был добавлен в настройках github:
<img width="866" height="240" alt="image" src="https://github.com/user-attachments/assets/6f233031-03ec-4e4c-8a87-483156d590a2" />
# 3. Проверка SSH-подключения к GitHub
с помощью команды ssh -T git@github.com устанавливаем соединение с github:
<img width="724" height="40" alt="image" src="https://github.com/user-attachments/assets/49260e7f-78cd-42eb-ac81-841c411269bd" />
# 4. Работа с репозиторием по SSH
Для клонирования репозитория используем команду git clone git@github.com:Zelebobr/Urfu-PI.git с помощью cd Urfu-PI переходим в нужный каталог и изменяем файл README, используем git add README.md и git commit:
<img width="576" height="101" alt="image" src="https://github.com/user-attachments/assets/33e63e1d-06da-4a3e-a985-eba8a7cffd02" />
## TEST COMMIT
378f024 (Test SSH push)
