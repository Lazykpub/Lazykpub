---
title:   Установка приложения в память устройства на ТВ LG
layout: default
---

#  Установка приложения в память устройства на ТВ LG с WebOS через Dev Manager

## Требования
— телевизор LG Smart TV с **webOS v3+**;  
— компьютер, на который будет устанавливаться программное обеспечение для доступа к телевизору в режиме разработчика.

## Инструкция
1. **Подготовка**
    - Создать аккаунт на сайте <a href="http://webostv.developer.lge.com" target="_blank" rel="noopener noreferrer">**http://webostv.developer.lge.com/**</a>.
      При регистрации использовать почту в зоне .com.
    - Подключить телевизор в ту же сеть, что и компьютер.
    - Установить на компьютер приложение <a href="https://github.com/webosbrew/dev-manager-desktop/releases/" target="_blank" rel="noopener noreferrer">**Dev Manager**</a>.
2. **На телевизоре**
    - отключить в настройках **Быструю загрузку**;
    - установить приложение **Developers mode** из **LG store content**;
    - запустить **Developers mode** и ввести логин/пароль вашей учетной записи <a href="http://webostv.developer.lge.com" target="_blank" rel="noopener noreferrer">**http://webostv.developer.lge.com/**</a>;
    - включить **Dev Mode** и **Key Server**.
3. **На компьютере, запустив приложение Dev Manager**
     - нажать на кнопку **+Add Device**;
     - в появившемся окне заполнить поля **Host** (введите IP адрес из приложения **Developers mode**) и **Passphrase** (также из приложения **Developers mode**);
     - скачать приложение для WebOS по ссылкам:  
       <a href="https://cdnservices.link/dl/webos/kinopub.tv.ipk" target="_blank" rel="noopener noreferrer">**запуск через меню приложений**</a>  
       <a href="https://cdnservices.link/dl/webos/kinopub_amazon.ipk" target="_blank" rel="noopener noreferrer">**запуск через кнопку Amazon на пульте**</a>  
       <a href="https://cdnservices.link/dl/webos/kinopub_ivi.ipk" target="_blank" rel="noopener noreferrer">**запуск через кнопку ivi на пульте**</a>
       <a href="https://cdnservices.link/dl/webos/kinopub_netflix.ipk" target="_blank" rel="noopener noreferrer">**запуск через кнопку Netflix на пульте**</a>
       <a href="https://cdnservices.link/dl/webos/kinopub_youtube.ipk" target="_blank" rel="noopener noreferrer">**запуск через кнопку YouTube на пульте**</a>
       <a href="https://cdnservices.link/dl/webos/kinopub.tv_movies_lg-cinema.ipk" target="_blank" rel="noopener noreferrer">**запуск через кнопку Movies (LG Cinema) на пульте**</a>
       <a href="https://cdnservices.link/dl/webos/kinopub.tv_movies_rakuten-tv.ipk" target="_blank" rel="noopener noreferrer">**запуск через кнопку Movies (Rakuten TV) на пульте**</a>
      Оригинальные приложения необходимо удалить.
    - в **Dev Manager** выбрать пункт меню Install и установить приложение.
4. ‼️**ВАЖНО**  
   У режима разработчика на телевизоре есть таймер времени в **1000 часов**, после окончания которого, согласно информации с официального сайта LG, установленные через режим разработчика приложения удаляются.
   
   Непродление режима разработчика может привести к удалению установленных приложений. Оставшееся количество часов текущей сессии можно посмотреть на телевизоре в приложении **Developer mode**, пункт **Remain Session**.
   
   Чтобы не допустить удаления установленных приложений нужно до истечения 1000 часов зайти на телевизоре в приложение **Developer mode** и продлить режим разработчика, нажав кнопку **EXTEND** напротив пункта меню **Extend Session Time**. Это запустит новую сессию на 1000 часов.
   
   Если 1000 часов прошло, вы не продлили режим разработчика, и установленные приложения были удалены, то вам нужно будет снова залогиниться на телевизоре в приложении **Developer mode**, и повторить установку.<br><br>

---
<p align="right"><a href="https://lazykpub.github.io/Lazykpub/pages/smarttv">Вернуться к списку Smart TV</a></p>
