# turkish_inflation


--------------------------------eng--------------------------------

Task: to estimate the impact of the Central Bank's key rate on inflation using a randomly selected economy as an example. Take data from open sources. Based on the results, prepare and present a report on the work done.

I decided to choose Turkey due to the current economic situation in the country. It was interesting to understand this. Also, the data was in open sources.

During the work, a linear regression model was built, the most significant factors influencing inflation were identified, and a list of recommendations and conclusions was prepared.

The final model has some shortcomings:
1) Raw data was used. When working with time series, this is not the best way to build models. Most often, time data is not standardized, which distorts the results of the model. Ideally instead of raw data (for example, usd/tur exchange rate), take rate of growth (how the data changes since last period). Then the model should be better.
2) The model was built incorrectly on lags. The previous lag of the target variable was not added as explanatory variables, although this could have improved the overall accuracy of the model.
   
--------------------------------ru--------------------------------

Задание: С помощью эконометрического инструментария оценить влияние учетной ставки Центробанка на инфляцию на примере произвольно выбранной экономики. Данные брать из открытых источников. По итогам подготовить и презентовать отчет о проделанной работе.

Я решил выбрать Турцию ввиду текущей экономической ситуации в стране. Было интересно разобраться в этом. Также данные были в открытых источниках.

В ходе работы была построенна модель линейной регрессии, выявлены наиболее значимые факторы влияющие на инфляцию, а также подготовлен список рекомендаций-выводов.

Финальная модель осталась не без проблем:
1) Использовались сырые данные. Работая с временными рядами - это не лучший способ построения моделей. Чаще всего временные данные не стандартизированы, что искажает результаты модели. В идеале, здесь, вместо сырых данных (напр., значение курса usd/tur) брать приросты (то, как данные меняются со временем). Тогда модель должна получиться лучше.
2) Неправильно строилась модель на лагах. Предыдущий lag целевой переменной не был добавлен в качестве объясняющих переменных, хотя это могло бы повысить общую точность модели.
