## Баг-репорт

**Заголовок:** Кнопка "Add to cart" выходит за пределы карточки товара

**Описание:** На странице каталога [https://www.saucedemo.com/inventory.html](https://www.saucedemo.com/inventory.html) кнопка “Add to cart” выходит за пределы карточки у товара "Test.allTheThings() T-Shirt (Red)"

**Фактический результат**

Кнопка "Add to cart" выходит за пределы карточки и выбивается из общей структуры 

**Ожидаемый результат**

Кнопка “Add to cart” полностью помещается внутри карточки товара, выровнена по центру и визуально согласована с остальными карточками 

**Шаги по воспроизведению**

- Открыть сайт https://www.saucedemo.com/

- Ввести валидный логин (visual_user)

- Ввести валидный пароль (secret_sauce)

- Нажать на кнопку "Login"

- На отображаемой странице [https://www.saucedemo.com/inventory.html](https://www.saucedemo.com/inventory.html) найти товар "Test.allTheThings() T-Shirt (Red)"

**Окружение:** Linux 6.8.0-48-generic, Google Chrome 127.0.6533.99 

**Важность:** Minor

**Срочность:** Medium