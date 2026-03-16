# Домашнее задание к занятию «Система мониторинга Zabbix часть 2»
**Выполнил:** Чехлов Михаил


## Задание 1: создание шаблона с элементами данных, отслеживающими загрузку CPU и RAM хоста..

![Страница шаблона zabbix для мониторинга загрузки CPU и RAM хоста.](latest_data.png)
*Latest data: cpu, ram.*

![Страница шаблона](pictures_templates.png)
*Templates — «Test Template».*



## Задание 2: Установка Zabbix Agent

![Страница раздела **Configuration > Hosts** с двумя хостами и зелёными индикаторами доступности.]
*Статус хостов (status - enabled).*

![Страница лог агента `sudo tail -f /var/log/zabbix/zabbix_agentd.log`]
*Status zabbix-agent — active(running).*

![Страница раздела **Monitoring > Latest data** с данными от обоих хостов.]
*Все отображённые метрики имеют статус normal*
