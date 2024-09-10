# Домашнее задание к занятию «Сетевое взаимодействие в K8S. Часть 1»

## Задание 1. Создать Deployment и обеспечить доступ к контейнерам приложения по разным портам из другого Pod внутри кластера

- Создаем манифесты для деплоймента, сервиса и отдельного пода

  ![image](https://github.com/user-attachments/assets/dc2bd31d-6764-4a40-8c94-1839ad9d75fd)

- Применяем все манифесты, проверяем, что все поднялось

  ![image](https://github.com/user-attachments/assets/114dbe6b-7945-489b-bc90-e708e9334e8d)

- Проверяем доступ внутри кластера из отдельного пода до подов деплоймента и до сервиса по ip и доменному имени

  ![image](https://github.com/user-attachments/assets/080c98b3-fa82-4d30-8edf-0f7204d433d3)
  ![image](https://github.com/user-attachments/assets/5d5b5d51-4e6d-43a6-8ad3-d69325bca7db)
  

## Задание 2. Создать Service и обеспечить доступ к приложениям снаружи кластера

- Создаем сервис для доступа по NodePort
  ![image](https://github.com/user-attachments/assets/4aeee8a8-c9b9-40f0-a89b-9817473416d4)
  ![image](https://github.com/user-attachments/assets/f29f2f05-e19e-4122-ab65-39b80bc1f937)
  ![image](https://github.com/user-attachments/assets/823d8646-231a-4226-a862-8f271e66f59a)

- Проверяем доступность сервиса с локального PC

  ![image](https://github.com/user-attachments/assets/982a2d18-e77a-4e8b-abe9-f5ba522980e0)
  ![image](https://github.com/user-attachments/assets/4150a817-94f0-4049-83e6-f084d83bf484)
