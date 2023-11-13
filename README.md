# LR6
Лабораторная работа №6
1. Аккаунт GitHub был создан до выполнения лабораторной работы ([ссылка])
2. Сделана копия в личное хранилище (Fork)
   
    ![1](https://github.com/shad0wcs/LR6/assets/113517738/7708cee2-5678-4645-84c0-bc49255a7a3a)

   
3. Git был установлен до выполнения лабораторной работы 
4. Настройка клиента git

    Изменено имя пользователя.
    ```sh
    git config --global user.name "4216 Колотов А.В."
    ```
    Изменен email.
    ```sh
    git config --global user.email "kolotov2004@list.ru"
    ```
    ![2](https://github.com/shad0wcs/LR6/assets/113517738/8fad666f-47cc-4baa-819e-51f0af575fb3)
    
5. Клонирован свой личный удалённый репозиторий на компьютер
    ```sh
    git clone https://github.com/shad0wcs/LR6.git
    ```
    ![3](https://github.com/shad0wcs/LR6/assets/113517738/e587c5d0-12ab-4600-90b9-e6cb63e072f7)

6. Добавлен файл через интерфейс GitHub, подтянуты изменения в локальный репозиторий
    Добавлен файл через интерфейс GitHub.

    ![4](https://github.com/shad0wcs/LR6/assets/113517738/3d25c882-002e-477c-915f-6e502ebbbb23)

    Подтянуты изменения в локальный репозиторий.
    ```sh
    git pull
    ```
    ![5](https://github.com/shad0wcs/LR6/assets/113517738/cb0b3344-e9d7-4273-b12e-074ca0752f63)

7. Получена история операций для каждой из веток
    Для master
    ```sh
    git log
    ```
    ![6](https://github.com/shad0wcs/LR6/assets/113517738/2e6b577c-a3ab-4182-8f04-a0dc3be7166f)

    Для branch1
    ```sh
    git log origin/branch1
    ```
    
    ![7](https://github.com/shad0wcs/LR6/assets/113517738/f17b2e7b-1511-4c75-adce-172979fdcf33)

    
8. Просмотрены последние изменения
    ```sh
    git status
    ```
    
    ![8](https://github.com/shad0wcs/LR6/assets/113517738/ea2c7548-92a5-4da2-8907-158d8b324f67)

    
9. Выполнено слияние в ветку master, разрешив конфликт
    Слияние веток.
    ```sh
    git merge branch1
    ```
    
    ![9](https://github.com/shad0wcs/LR6/assets/113517738/19e14c6c-2a39-44f0-94b0-6e354dce42c0)

    
    Конфликт решен с помощью графического интерфейса.
    
    ![10](https://github.com/shad0wcs/LR6/assets/113517738/a3f2934d-1117-4b22-ac7b-46408813115c)

    
    Зафиксированы изменения.
    ```sh
    git add mergefile.txt
    git commit -m"Конфликт решен"
    ```
    
    ![11](https://github.com/shad0wcs/LR6/assets/113517738/2afc10c8-407a-4ae7-b369-5ebf47762240)

    
10. Удалена побочная ветка после успешного слияния
    
    При слиянии ветка удалилась автоматически.

    ![12](https://github.com/shad0wcs/LR6/assets/113517738/d87316ea-5183-4e31-8ec8-61ca78fa793a)

    
    Удаление ветки на GitHub
    ```sh
    git push origin -d branch1
    ```
    
    ![13](https://github.com/shad0wcs/LR6/assets/113517738/4770d4da-7f7f-4acb-a0ff-e18803d71f90)

    
11. Изменения сделаны и зафиксированы
    
    Первое изменене.

    ![14](https://github.com/shad0wcs/LR6/assets/113517738/e04a158a-1c72-413d-9046-75690fe51df3)

    Второе изменение.

    ![15](https://github.com/shad0wcs/LR6/assets/113517738/66b35cc3-010c-44c5-be45-c02fbc992e83)

12. Сделан откат коммита
    
    ```sh
    git reset --hard HEAD~
    ```
    До отката:

   ![16](https://github.com/shad0wcs/LR6/assets/113517738/e5e2dacc-bb86-4f15-a067-c69a3e222828)


    После отката:
    
  ![17](https://github.com/shad0wcs/LR6/assets/113517738/ed660731-b149-48f0-9b50-66199d30336d)

13. Создана ветка для отчета

    ![18](https://github.com/shad0wcs/LR6/assets/113517738/fde85f6c-6ee8-4085-9d60-7f915be2d4ba)


14. Получена история операций в форматированном виде
    
    ![20](https://github.com/shad0wcs/LR6/assets/113517738/2075f40e-be44-44cb-a8d3-a8c9c61eb620)



   [ссылка]: [https://github.com/shad0wcs]
