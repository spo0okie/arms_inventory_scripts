# puppet_inventory_scripts
Внешние скрипты для работы с БД инвентаризации для Linux ОС  
*проверено только на Centos*

Сделано сразу в одном репозитории и код самих скриптов и puppet-обвязка для их пуша, 
т.к. без распространения этих скриптов, смысла в них мало.

требует redhat-lsb-core, smartmontools  

именование линукс машин по следующему соглашению
hostname -f должен возвращать fqdn хоста  
это решается этим модулем:  
https://github.com/spo0okie/puppet_centos_hostname/tree/master
