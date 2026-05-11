<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>SMART HOME</title>
    <link rel="stylesheet" href="smart.css">
</head>
<body> 
    <header>
        <div class="header-container">
            <img src="beb.png" class="logo" alt="Logo">
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Access Control</a></li>
                    <li><a href="#">Digital</a></li>
                </ul>
            </nav>
            <form>
                <input type="search" name="p" placeholder="Search">
            </form>
            <div class="socies">
                <a href="#"><img src="Instagram.png" alt="Inst"></a>
                <a href="#"><img src="Facebook.png" alt="Fb"></a>
                <a href="#"><img src="Twitter.png" alt="Tw"></a>
                <a href="#"><img src="WhatsApp.png" alt="Wa"></a>
            </div>
        </div>
    </header>

    <main>
        <div class="info-section">
            <p> 
                <img src="control.png" width="250" alt="control" border="2" style="float: left; margin: 10px;"> 
                Полный контроль над домом даже на расстоянии — можно выключить свет, проверить камеры, закрыть дверь или отключить утюг с телефона.
                Автоматизация рутины — свет сам включается вечером, шторы открываются утром, кондиционер подстраивается под температуру.
            </p>
            
            <p style="text-align: right; clear: both;">
                <img src="variety.png" width="250" alt="variety" border="2" style="float: right; margin: 10px;">
                Гибкие сценарии — один режим может менять сразу всё: освещение, музыку, температуру, технику. Например «Сон», «Кино», «Работа», «Я ушёл». Высокая вариативность устройств — можно комбинировать лампы, датчики, колонки, розетки, замки, камеры и делать систему под себя.
            </p>
          
            <p style="clear: both;"> 
                <img src="reliability.jpg" width="250" alt="reliability" border="2" style="float: left; margin: 10px;">  
                Надёжность умного дома: Умный дом способен повысить безопасность и стабильность жизни в доме благодаря автоматическому контролю систем. Датчики могут обнаруживать утечки воды, газа, дым или проникновение в помещение.
            </p>

            <p style="text-align: right; clear: both;"> 
                <img src="eco.png" width="250" alt="eco" border="2" style="float: right; margin: 10px;"> 
                Экологическая результативность: Умный дом помогает экономить ресурсы и уменьшать лишнее потребление энергии. Освещение и техника автоматически отключаются, когда они не нужны.
            </p>
        </div>

        <table width="100%">
            <tr>
                <td align="center">
                    <span style="font-family: Arial; font-size: 40px; color: #ffffff;">Пример работы:</span>
                </td>
            </tr>
        </table>

        <div class="wrapper">
            <input type="checkbox" id="bg-switch" class="toggle-checkbox">
            <label for="bg-switch" class="toggle-label">
                <span class="toggle-inner"></span>
            </label>

            <div class="content">
                <h1>Включить свет</h1>
                <p>Нажми на переключатель выше!</p>
            </div>
        </div>

        <img src="plant.gif" width="100%" alt="animation">
    </main>
</body>
</html>
