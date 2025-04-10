# Блокчейн мережі

[![](https://img.youtube.com/vi/gSWO_hygZEA/0.jpg)](https://www.youtube.com/watch?v=gSWO_hygZEA)

У цьому уроці ми поговоримо з Вами про гаманці, їхні типи та дізнаємося що таке сід-фраза.

**Гаманець** - інструмент, за допомогою якого ви можете взаємодіяти з будь-якою мережею, отримувати\відправляти\зберігати на ньому кошти та інше.

Будь-який гаманець, це лише красива обкладінка (UI). Якщо ви використовуєте "MetaMask" (або будь-який інший гаманець), то ваші кошти зберігаються не на метамасці, а в блокчейні, а метамаск - гарно їх відображає в зручному розширенні\додатку.

**Гаманці діляться на два типи:**
---------------------------------

1.  Холодний. Наприклад: Ledger \ Trezor \ SafePal.
2.  Гарячий. Наприклад: MetaMask \ Coin98 \ TrustWallet.

**Холодний** - гаманець, який не має зв'язки з інтернетом (фізичний гаманець, який ви можете пощупати, заховати та інше).

**Гарячий** - будь-який вид гаманця, який підключений до інтернету (той гаманець, який ви використовуєте в браузері/телефоні).

**Що таке сід-фраза?**
----------------------

**Сід-фраза** - це набір із 12 або більше слів, який використовується для відновлення доступу до гаманця.

За фактом, сід-фраза - це найголовніше, що є у Вас від гаманця, саме вона дає повний доступ до коштів, які зберігаються на ньому.

У разі, якщо Ви створили гаманець, отримали Сід-фразу і поділилися нею, наприклад зі мною, цей гаманець більше не Ваш, а вже наш. І я точно так само як і Ви, можу повністю розпоряджатися всіма коштами, які зберігаються на гаманці.

Запам'ятайте, сід-фраза генерується один раз і залишається незмінною протягом усього часу. Змінити її через час не можна.

**Як генерується сід-фраза?**
-----------------------------

Якщо Вам дуже цікаво як це працює, Ви можете прочитати цю [статтю від Ledger](https://support.ledger.com/hc/ru/articles/4415198323089-%25D0%259A%25D0%25B0%25D0%25BA-%25D1%2583%25D1%2581%25D1%2582%25D1%2580%25D0%25BE%25D0%25B9%25D1%2581%25D1%2582%25D0%25B2%25D0%25BE-Ledger-%25D0%25B3%25D0%25B5%25D0%25BD%25D0%25B5%25D1%2580%25D0%25B8%25D1%2580%25D1%2583%25D0%25B5%25D1%2582-%25D1%2584%25D1%2580%25D0%25B0%25D0%25B7%25D1%2583-%25D0%25B2%25D0%25BE%25D1%2581%25D1%2581%25D1%2582%25D0%25B0%25D0%25BD%25D0%25BE%25D0%25B2%25D0%25BB%25D0%25B5%25D0%25BD%25D0%25B8%25D1%258F-%25D0%25B8%25D0%25B7-24-%25D1%2581%25D0%25BB%25D0%25BE%25D0%25B2-?docs=true) (один з найпопулярніших холодних гаманців).

Цей алгоритм актуальний для всіх сучасних гаманців. Не важливо, це холодний чи гарячий гаманець, адже всі вони працюють за одним стандартом - BIP39.

Саме тому, сід-фраза від одного гаманця, підходить до іншого гаманця та інший гаманець, в який Ви імпортували сід-фразу, так само може відобразити всі ваші кошти. Єдине що зміниться - інтерфейс.

**Чи можливо підібрати сід-фразу?**
-----------------------------------

Кількість варіантів сід-фрази (за умови 24 слів) - 2^256 (2 у ступені 256).

Кількість атомів на Землі оцінюється приблизно в 2^166.

Тому, шанс підібрати сід-фразу від вашого гаманця близький до нуля.

**Чи можна відновити сід-фразу?**
---------------------------------

Ні, це неможливо. У разі втрати ви повністю і назавжди втратите доступ до своїх коштів.

**Холодний гаманець** - найбезпечніший спосіб зберігання своїх криптозасобів

Найголовніша перевага холодного гаманця - він не має доступу в інтернет. Плюс до цього, щоб відправити кошти, вам потрібно не просто натиснути "апрув" десь у застосунку, а потрібно мати фізично гаманець при собі, вести пароль від нього, після цього ви подивитеся деталі транзакції (переконайтеся, чи правильно ви вказали суму переказу\адресу одержувача) і тільки після цього натиснете "апрув" фізичними кнопками.

Як виглядає холодний гаманець Ledger (виглядає як звичайна флешка):

****![](https://lh5.googleusercontent.com/JSpNS4KaKCfqeQ6n-snCMpVR9xtgAEWq6tWqsNHTBX8HIppYd2uWzEaFuBIzXEHObt-L1QSHdOsOkc2kq3SFXBH0I5lajxjkrI7VpalLzhQHzokhHxkiPu09-PAvkb77yNufkBof62MglFx19pG0lU4)****

Найпопулярніші холодні гаманці:

1. [Ledger](https://www.ledger.com/ru)

2. [Trezor](https://trezor.io/)

3. [Safepal](https://safepal.io/)

У статті ми вказали посилання на офіційні сайти, якщо Ви хочете купити собі холодний гаманець, використовуйте тільки офіційні сайти, ніяких реселерів.

**Що буде, якщо я втрачу холодний гаманець? Я не зможу отримати доступ до своїх коштів?**

Ваші кошти в безпеці. Знову згадуємо що вони НЕ зберігаються на гаманці, а зберігаються в БЧ. У разі, якщо ви загубили холодний гаманець (фіз.пристрій), без нього ви не зможете переказати кошти, так як під час відправки, потрібно фізично підтвердити транзакцію.

Якщо гаманець все таки загублений, то існує 2 варіанти, як отримати доступ до своїх коштів:

1.  Замовити будь-який холодний гаманець (Навіть якщо у вас був Ledger, ви можете замовити Trezor) та інтегрувати в нього сід-фразу від попереднього гаманця, тим самим, отримавши доступ до своїх коштів.
2.  Взяти свою сід-фразу і завантажити будь-який гарячий гаманець (MetaMask\Coin98\TrustWallet\інше) та інтегрувати свою сід-фразу до нього. Ви також отримаєте доступ до своїх коштів, тільки в такому способі є одне АЛЕ, після подібного Ваш гаманець перетвориться на гарячий (оскільки він отримав доступ до інтернету) і відповідно стане менш безпечним, ніж гарячий.

**Чи безпечний гарячий гаманець?**
----------------------------------

Ми більшу частину уроку нахвалювали холодні гаманці за їхню безпеку і у Вас могло скластися враження, що гарячий гаманець небезпечний, але це не так.

Він точно безпечніший за будь-яку біржу, адже ваші кошти повністю належать Вам, і якщо Ви правильно зберігатимете свою сід-фразу і не підписуватимете різноманітні "незрозумілі" транзакції на сумнівних сайтах, то Ваш гарячий гаманець буде не менш безпечним, ніж холодний.

Про те, як ви можете втратити свої кошти, просто підписавши якусь транзакцію на фішинговому сайті, ми поговоримо з Вами в уроці "Скам у крипті і як від нього захиститися".

Але підсумок один - якщо Ви правильно зберігаєте сід-фразу і не "гуляєте" фішинговими сайтами, ваші кошти в цілковитій безпеці.

**Вибір редакції**
------------------

Якщо у вас є питання, якими ж гаманцями користується **DOUBLETOP**, відповім:

1.  [MetaMask](https://metamask.io/) (EVM wallet).
2.  [Ledger](https://www.ledger.com/ru/%D0%B3%D0%BB%D0%B0%D0%B2%D0%BD%D0%B0%D1%8F) (холодний гаманець).
3.  [TrustWallet](https://trustwallet.com/ru/) \- дуже зручний для переказів у мережі Tron.

Ці 3 гаманці - найбільш часто використовувані в повсякденному житті криптана.

Решта гаманців, на кшталт **Phantom** (гаманець екосистеми Solana), **Keplr** (гаманець екосистеми Cosmos), **PolkadotJs** (гаманець екосистеми DOT\KSM), є більш ситуативними і загалом вибору щодо них не надається, тож користуємося ними, адже вони просто зручні, у своїх екосистемах. Ну і ще, пам'ятайте, вибір гаманця - смаківщина. Користуйтеся тим - що Вам зручно.

**До зустрічі в наступному уроці!**