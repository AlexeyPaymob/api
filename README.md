# api

## Если пришел пользователь не с мобильного оператора. 

1. У подписки будет установлен статус ERR_NOT_MOBILE_IP
2. Будет отправлен на трафик-бек с кодом ERR_NOT_MOBILE_IP 
3. Не будет засчитан в статистике по трафику (временное решение).
4. Информация о подписке будет удалена через 15 минут.
5. Уведомления не вызываются
