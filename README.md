# «Аналитик данных» проекты:
Этот репозиторий посвящен учебным проектам, которые я выполнила за время прохождения курса по 
«Анализу Данных» на Яндекс.Практикуме.

Программа обучения помогла мне научиться исследовать, обрабатывать и систематизировать данные, 
выявлять закономерности, делать предположения и четко сообщать важные выводы.

<table>
   <thead valign="top">
    <tr>
     <td>Название проекта</td>
     <td>Описание</td> 
     <td>Использованные библиотеки</td> 
    </tr> 
   </thead>
   <tbody  valign="top">
    <tr>
     <td>
      <b>
       01: <a href="https://github.com/deliriumdel/portfolio/tree/master/01_credit-scoring-preprocessing">
       Исследование надежности заемщиков</a>
      </b>
     </td>
     <td>
        Определила, влияет ли семейное положение и количество детей на погашение кредита в срок.<br>
        Использовала лемматизацию, категоризацию и последующий анализ групп клиентов.
     </td>
     <td>
        <code>
            pandas<br>
            pymystem3<br>
            Counter (from collections)
        </code>
     </td>
    </tr>
    <tr>
     <td>
      <b>
       02: <a href="https://github.com/deliriumdel/portfolio/tree/master/02_research-of-apartment-advertisements">
       Исследование объявлений о продаже квартир</a>
      </b>
     </td>
     <td>
        Провела исследовательский анализ рынка жилья, составила типовую выборку и на ее основании изучила
        влияние различных факторов на стоимость недвижимости.<br>
        Установила параметры для определения рыночной стоимость объектов недвижимости, чтобы остлеживать аномалии и 
        мошенническую деятельность на сайте он-лайн сервиса.<br>
     </td>
     <td>
        <code>
            pandas<br>
            matplotlib.pyplot<br><br>
            Визуализации: boxplot, histogram, scatterplot, line plot.
        </code>
     </td>
    </tr>
    <tr>
     <td>
      <b>
       03: <a href="https://github.com/deliriumdel/portfolio/tree/master/03_telecom">
       Определение перспективного тарифа для телеком компании</a>
      </b>
     </td>
     <td>
        Подобрала типовые характеристики пользователей, исследовала использование ресурсов оператора, определила, какой 
        тариф приносит больше денег, чтобы перераспределить бюджеты на рекламу.
     </td>
     <td>
        <code>
            pandas<br>
            math<br>
            matplotlib.pyplot<br>
            stats from scipy<br>
            numpy<br><br>
            Визуализации: boxplot, histogram.
        </code>
     </td>
    </tr>
    <tr>
     <td>
      <b>
       04: <a href="https://github.com/deliriumdel/portfolio/tree/master/04_e-commerce-games">
       Исследование рынка компьютерных игр</a>
      </b>
     </td>
     <td>
        Провела исследовательский анализ данных о продажах игр, составила портрет пользователей из каждого региона, 
        спрогнозировала приоритетные направления для продаж на следующий год.
     </td>
     <td>
        <code>
            pandas<br>
            matplotlib.pyplot<br>
            stats from scipy<br>
            numpy<br><br>
            Визуализации: boxplot, histogram, line plot, group bar, scatterplot.
        </code>
     </td>
    </tr>
    <tr>
     <td>
      <b>
       05: <a href="https://github.com/deliriumdel/portfolio/tree/master/05_ticket_service-business-analysis">
       Аналитика в интернет-сервисе по продаже билетов</a>
      </b>
     </td>
     <td>
        Провела исследование и рассчитала метрики: DAU, WAU, MAU, sticky factor, Retention Rate, LTV, SAS, ROMI.<br>
        Выяснила как люди пользуются продуктом, когда они начинают покупать, сколько денег приносит каждый клиент, 
        когда клиент окупается. 
     </td>
     <td>
        <code>
            pandas<br>
            matplotlib.pyplot<br>
            seaborn<br>
            numpy<br><br>
            Визуализации: boxplot, histogram, line plot, heatmap, group bar, stacked bar.
        </code>
     </td>
    </tr>
    <tr>
     <td>
      <b>
       06: <a href="https://github.com/deliriumdel/portfolio/tree/master/06_e-commerce-a-b-testing">
       Принятие решений в бизнесе на основе данных</a>
      </b>
     </td>
     <td>
        Приоритизировала гипотезы, проанализировала данные, полученные за время проведения А/В теста: кумулятивная 
        выручка, средний чек и конверсия по группам. 
        Проанализировала статистическую значимость с помощью критерия Манна-Уитни: конверсии, различий в среднем чеке 
        между группами, сырыми и очищенными данными.
     </td>
     <td>
        <code>
            pandas<br>
            matplotlib.pyplot<br>
            matplotlib.lines<br>
            numpy<br>
            datetime<br>
            scipy.stats
        </code>
     </td>
    </tr>
    <tr>
     <td>
      <b>
       07: <a href="https://github.com/deliriumdel/portfolio/tree/master/07_restaurants-vizualization">
       Анализ рынка заведений общественного питания Москвы</a>
      </b>
     </td>
     <td>
        Провела исследовательский анализ данных о заведениях общественного питания Москвы.<br>
        Cделаkf общий вывод и даkf рекомендации о виде заведения, количестве посадочных мест, а также районе 
        расположения для открытия небольшого кафе.
     </td>
     <td>
        <code>
            pandas<br>
            plotly.express<br>
            re<br>
        </code>
     </td>
    </tr>
    <tr>
     <td>
      <b>
       08: <a href="https://github.com/deliriumdel/portfolio/tree/master/08_conversion%20funnel_and_AB">
       Анализ мобильного приложения продуктового магазина. Воронка продаж, А/А/В-тест</a>
      </b>
     </td>
     <td>
        Изучила воронку конверсии, проанализировала все шаги, которые покупатель проходит до покупки, выявила вероятные 
        проблемы. Исследовала результаты проведенного А/А/В-теста, чтобы выяснить, какой шрифт лучше.
     </td>
     <td>
        <code>
            pandas<br>
            plotly.express<br>
            numpy<br>
            math<br>
            proportions_ztest from statsmodels.stats.proportion
        </code>
     </td>
    </tr>
    <tr>
     <td>
      <b>
       09: <a href="https://public.tableau.com/views/Dashboard_first_portfolio/Dashboard1?:language=en&:display_count=y&publish=yes&:origin=viz_share_link">
       Анализ взаимодействия пользователей с карточками Яндекс.Дзен</a>
      </b>
     </td>
     <td>
        Дашборд для менеджеров по анализу контента.<br>
        Сагрегировала данные и сверстала дашборд с основными типами графиков и элементами управления.
        (в первоначальном варианте проект был выполнен на локальной машине с помощью dash, но позже я разобралась с 
        Tableu.Public и разместила в сети в этом варианте)
     </td>
     <td>
        <code>
            pandas<br>
            dash<br>
            dash_core_components<br>
            dash_html_components<br>
            dash.dependencies<br>
            datetime<br>
            plotly.graph_objs
        </code>
     </td>
    </tr>
    <tr>
     <td>
      <b>
       10: <a href="https://github.com/deliriumdel/portfolio/tree/master/10_ML">
       Применение машинного обучения в прогнозировании оттока клиентов фитнес-центра</a>
      </b>
     </td>
     <td>
        Провела исследовательский анализ данных о клиентах, проанализировалла корреляцию признаков.<br>
        Построила модель прогнозирования оттока клиентов.
     </td>
     <td>
        <code>
            pandas<br>
            matplotlib.pyplot<br>
            seaborn<br><br>
            train_test_split from sklearn.model_selection<br>
            StandardScaler from sklearn.preprocessing<br>
            LogisticRegression from sklearn.linear_model<br>
            RandomForestClassifier from sklearn.ensemble<br>
            accuracy_score, precision_score, recall_score, f1_score, roc_auc_score from sklearn.metrics<br>
            RandomizedSearchCV from sklearn.model_selection<br>
            dendrogram, linkage from scipy.cluster.hierarchy<br>
            KMeans from sklearn.cluster
        </code>
     </td>
    </tr>
    <tr>
     <td>
      <b>
       11: <a href="https://github.com/deliriumdel/portfolio/tree/master/11_AB_SQL_E-commerce_Dashboard">
       Анализ проведенного АВ-тестирования, запросы SQL, E-commerce, дашборд</a>
      </b>
     </td>
     <td>
        <ol>
         <li>Анализ проведенного АВ тестирования.</li>
         <li>SQL-запросы.</li>
         <li>E-commerce — Выявление профилей потребления.</li>
         <li>Дашборд.</li>
        </ol>
     </td>
     <td>
        <code>
            pandas<br>
            plotly.express<br>
            numpy<br>
            math<br>
            proportions_ztest from statsmodels.stats.proportion<br><br>
            create_engine from sqlalchemy<br><br>
            datetime<br>
            pyplot from matplotlib<br>
            seaborn<br>
            stats from scipy
        </code>
     </td>
    </tr>
   </tbody>
</table>