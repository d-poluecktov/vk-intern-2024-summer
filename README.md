<h1>vk-intern-2024-summer</h1>
<h2>Условие:</h2>
Дан тренировочоный датасет с текстами сообщений из мессенджера на английском языке. Для каждого из них проставлен флаг того, является ли сообщение СПАМом.
Так же дан тестовый датасет с такими же текстами сообщений, но без флага. На нем нужно будет проскорить модель и проложить результаты.
<h2>Описание данных:</h2>
<ol>
<li>text_type - целевая переменная, флаг СПАМ/не СПАМ.</li>
 <li>text - текст сообщения.</li>
</ol>
<h2>Требования:</h2>
<ol>
<li> провести базовую аналитику по имеющимся данным.</li>
<li>обучить модель по тексту сообщения определять, является ли ее содержиоме СПАМом (ожидается, что будут опробованы несколько подходов, из которых аргументировано выбирается наилучший; можно использовать любую библиотек или фреймворк)
<li>целевой метрикой является ROC-AUC score</li>
<li>произвести скоринг лучшей моделью тестовых данных, а результат записать в csv-файл в виде таблицы с колонками score и text</li>
<li>выложить код на github</li>
</ol>
<h2>Решение:</h2>
<ol>
  <li>spam_classification.ipynb - ноутбук с кодом-решением</li>
  <li>submission.csv - проскореный тестовый файл</li>
</ol>
