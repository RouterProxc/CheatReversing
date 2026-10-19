# CheatReversing

Реверсим мобильный инжектор чита для SO2

Открываем файл весом ~13мб в JADX

Переходим в AndroidManifest.xml 


<img width="762" height="702" alt="image" src="https://github.com/user-attachments/assets/b3e9215b-c92d-46f6-bb70-43c7fc68e971" />


Видим MainActivity - переходим внутрь

<img width="2560" height="192" alt="image" src="https://github.com/user-attachments/assets/0892d438-94e7-49f3-b2d6-82ebf425d8af" />

В целом методов не много - но ниже выделю основные из них

<img width="728" height="196" alt="image" src="https://github.com/user-attachments/assets/f0235a14-df13-43ba-80b6-bf9b9303dbf3" />

Вот основная логика лицензирования чита

<img width="1384" height="952" alt="image" src="https://github.com/user-attachments/assets/9423a999-fd10-442a-a67f-32158ffdcbd2" />


