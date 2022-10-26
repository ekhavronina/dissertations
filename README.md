# dissertations
Проектная работа, выполненная для курса по NLP (весна 2022), в которой сравнивались два корпуса авторефератов диссертаций по истории из двух российских университетов с помощью тематического моделирования и меры TF-IDF.

Все авторефераты были загружены с сайта РНБ и находятся в открытом доступе.

Корпус РГСУ (метаданные находятся в файле rgsu.csv) содержит 195 авторефератов и 1,713М токенов до чистки. Корпус РГГУ (rggu.csv) содержит 262 автореферата и 2,270 токенов до чистки. Тексты авторефератов собраны в архивы в формате txt.

Файлы dis_RGGU.Rmd и dis_RGSU.Rmd содержат скрипты для препроцессинга и тематического моделирования в корпусах авторефератов докторских и кандидатских диссертаций по Отечественной истории, написанных или защищенных в РГГУ и РГСУ соответственно.

Файл dissers.Rmd содержит скрипт для классификации работ с помощью меры TF-IDF. Однако модель получилась сырая и плохо предсказывала, к какому корпусу относится та или иная диссертация.
