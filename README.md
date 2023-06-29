# javascript-project-10

Задание 1
Создать страницу, состоящую из 2-х блоков (на странице будет отображаться один из них по заданным условиям):
■ блок с формой регистрации;
■ блок с пользовательской информацией.
Первая страница, на которую попадает пользователь, это страница с блоком для регистрации.

После нажатия на кнопку Sign Up, необходимо проверить корректность введенных данных.

Почтовый адрес:
■ обязательное поле;
■ обязательно присутствие символа @ и домена после @; ■ до символа @ должно быть минимум 3 других символа.
Пароль:
■ обязательное поле;
■ минимум 6 символов;
■ обязательно должны присутствовать: 1 буква в нижнем регистре, 1 буква в верхнем регистре и 1 цифра.
Подтверждение пароля:
■ обязательное поле;
■ должно совпадать с данными в предыдущем поле.
Если данные введены некорректно, то необходимо вывести ошибки пользователю.

Если пользователь корректно введет все данные, то необходимо сохранить их в куки, скрыть данный блок и отобразить следующий блок с вводом дополнительных данных пользователя.
Когда пользователь заходит на страницу регистрации, необходимо проверять, присутствуют ли данные о пользователе в куки. Если присутствуют, то сразу перенаправлять его на блок с вводом дополнительных данных. Следующий блок – это блок с более подробной пользовательской информацией.

На этом блоке должна быть кнопка Exit и форма для ввода пользовательских данных.
По нажатию на кнопку Exit, данные из куки удаляются и пользователь перенаправляется на блок регистрации.
При нажатии на кнопку Save, необходимо проверять корректность введенных данных. Сделать свою валидацию для каждого из полей
Если данные введены некорректно, то необходимо вывести ошибки (как в форме регистрации). Если данные введены корректно, то необходимо сохранить их в куки.
Когда пользователь заходит на страницу с подробной информацией, необходимо проверять, присутствуют ли эти данные в куки. Если данные в куки присутствуют, то выводить их на форме. Если не присутствуют, то оставлять форму пустой.
Если пользователь заходит на страницу с подробной информацией, а в куки вообще нет никакой информации, то необходимо перенаправить его на блок регистрации.
Максимальный срок жизни всех куки – 1 час.



Exercise 1
Create a page consisting of 2 blocks (one of them will be displayed on the page according to the specified conditions):
■ a block with a registration form;
■ block with user information.
The first page that the user gets to is the page with the registration block.

After clicking on the Sign Up button, you need to check the correctness of the entered data.

Mailing address:
■ required field;
■ mandatory presence of @ symbol and domain after @; ■ There must be at least 3 other characters before the @ symbol.
Password:
■ required field;
■ at least 6 characters;
■ must be present: 1 lowercase letter, 1 uppercase letter and 1 number.
Password confirmation:
■ required field;
■ must match the data in the previous field.
If the data is entered incorrectly, then it is necessary to display errors to the user.

If the user correctly enters all the data, then it is necessary to save them in cookies, hide this block and display the next block with additional user data.
When a user enters the registration page, it is necessary to check if the user data is present in the cookie. If present, then immediately redirect it to the block with the input of additional data. The next block is a block with more detailed user information.

This block should have an Exit button and a form for entering user data.
By clicking on the Exit button, the data from the cookie is deleted and the user is redirected to the registration block.
When you click on the Save button, you need to check the correctness of the entered data. Make your own validation for each of the fields
If the data is entered incorrectly, then it is necessary to display errors (as in the registration form). If the data is entered correctly, then it is necessary to save them in cookies.
When a user visits a page with detailed information, it is necessary to check if this data is present in the cookie. If the data in the cookie is present, then display it on the form. If not present, then leave the form blank.
If the user enters the page with detailed information, and there is no information in the cookie at all, then it is necessary to redirect him to the registration block.
The maximum lifetime of all cookies is 1 hour.
