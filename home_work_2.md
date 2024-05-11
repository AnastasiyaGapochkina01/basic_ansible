## Домашняя работа №2: Модули и плейбуки
1) Написать плейбук, который добавит на удаленный хост две группы:
- developers
- analysts
2) Написать плейбук, который создаст директорию /opt/ansible/tmp и скопирует туда файл requirements.txt со следующим содержимым
```
contourpy==1.0.6
cycler==0.11.0
fonttools==4.38.0
kiwisolver==1.4.4
matplotlib==3.6.2
numpy==1.23.5
packaging==21.3
pandas==1.5.1
pillow==9.3.0
pyparsing==3.0.9
python-dateutil==2.8.2
pytz==2022.6
scipy==1.9.3
seaborn==0.10.1
six==1.16.0
```
3) Написать плейбук, который установит на удаленный хост java
4) Написать плейбук, который выведет факты:
- ansible_distribution
- ansible_distribution_major_version
- ansible_fqdn