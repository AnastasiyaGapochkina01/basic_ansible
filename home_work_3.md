## Домашняя работа №3: Переменные
0) Подготовить две ВМ: одну с debian и вторую с centos
1) Написать плейбук, который установит на подготовленные ВМ в п.0 redis (имя пакетов для разных дистрибутивов отличается). На каком уровне определять переменные решите самостоятельно
2) Написать плейбук, который установит на подготовленные ВМ в п.0 ruby. На каком уровне определять переменные решите самостоятельно
3) Написать плейбук, который скопирует на подготовленные ВМ в п.0  файлы debian.envs и centos.envs в директорию /etc/ansible_facts
debian.envs
```
{
  "env": "dev",
  "project": "ansible",
  "team": "devops",
}
```
centos.envs
```
{
  "env": "prod",
  "project": "ansible",
  "team": "devops",
}
```
На каком уровне определять переменные решите самостоятельно
