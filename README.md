Необходимо реализовать форму обратной связи на Laravel:
 
-регистрация\авторизация: стандартный модуль auth (но пользователи должны быть с двумя ролями: менеджер и клиент.
Клиенты регистрируются самостоятельно, а аккаунт менеджера должен быть создан заранее, логин и пароль выслать вместе с готовым заданием)
-после логина, клиент видит форму обратной связи, а менеджер список заявок. (все страницы и функционал доступны только авторизованным пользователям и только в соответствии с их привилегиями)
-менеджер может просматривать список заявок и отмечать те, на которые ответил.
-список заявок:
*ID, тема, сообщение, имя клиента, почта клиента, ссылка на прикрепленный файл, время создания
 
-клиент может оставлять заявку, но не чаще раза в сутки.
 
-на странице создания заявки: тема и сообщение, файловый инпут кнопка "отправить".
-в момент обработки формы и создания заявки отправлять менеджеру email со всеми данными
