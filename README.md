
# Описание playbook
Устанавливаются Java, ElasticSearch, Kibana. Для Kibana прописываются пути до ElasticSearch в конфигурационных файлах.

Установлены тэги:
- Java
- Elastic
- Kibana

## Описание play

1. Install Java
   - установка переменных
   - загрузка установочного пакета
   - создание рабочего каталога
   - распаковка пакета
   - создание по шаблону переменных окружений

2. Install Elasticsearch
   - загрузка установочного пакета
   - создание рабочего каталога
   - распаковка в рабочий каталог из пакета
   - создание по шаблону переменных окружений 

3. Install Kibana
   - загрузка установочного пакета
   - создание рабочего каталога
   - распаковка в рабочий каталог из пакета
   - создание по шаблону переменных окружений

## Переменные  
group_vars\all
- `java_jdk_version` - версия пакета Java  
- `java_oracle_jdk_package` - имя пакета Java  
  
group_vars\elasticsearch
- `elastic_version` - версия Elasticsearch  
- `elastic_home` - переменная домашнего каталога Elasticsearch  
- 
group_vars\kibana
- `kibana_version` - версия Kibana  
- `kibana_home` - переменная для домашнего каталога Kibana  
