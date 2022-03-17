# siem

Цель проекта рализовать SIEM систему которая могла бы пониторить и выявляеть угрозы и атаки на следющие целевые системы:
  - [ ] Web приложение на NGINX PHP
  - [ ] Windows Server /LDAP
  - [ ] Web app on ApacheTomcat 
  - [ ] Web app on Jboss

SIEM-система реализующая мониторинг целевого приложениия/cистемы, выяляющего подзрительные события касающиеся кибер безопасности целового приложения/системы и уведомляющая об этом администратора.

В функциональность SIEM системы входит
1. Сбор и хранения событий кибер-безопасности
2. Обнаружение атак и нарушений политик безопасности
3. выявление инидентов кибер безопасности
4. формирование отчетов


Релизация состит из следующих частей 
- [ ] Созадать веб приложение на nginx 
- [ ] Взломать его и посмотреть как можно выявить взлом и отобразить его ы логах
- [ ] Написать SIEM систему 
- [ ] рализовать сбор инфформации из сервера nginx и реализации правил обнаружение и возможность уведомления


Типы кибератак которые должны быть обнаружены SIEM системой
 - [ ] Взлом учетной записи в приложении  на NGINX
 - [ ] Взлом сервера на nginx получении какой либо сессии
 - [ ] DDos атаки на сервер
 
 Уведомление администратора должно проходить следующим образом
 - [ ] Уведомление на панели администратора
 - [ ] Уведомление на почту
