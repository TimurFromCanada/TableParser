Полный проект и его описание можно скачать с ulearn.me (Основы программирования на примере C#. Часть 1)

В этой серии задач вам нужно реализовать парсер полей. Парсером обычно называют алгоритм, который из текста делает набор объектов, представленных в этом тексте.

Итак, на вход нашего парсера подается строка текста. В результате выполнения серии этих задач у вас получится алгоритм, возвращающий список полей, извлечённых из текста по описанным ниже правилам, либо пустой список, если полей в исходном тексте не оказалось. В этой задаче реализуйте один вспомогательный метод ReadQuotedField, для чтения полей в кавычках. В следующей задаче вам нужно будет воспользоваться этим методом.

В этой задаче вам не нужно реализовывать алгоритм. Вместо этого напишите набор тестов, который покрывает все основные ситуации для задачи, описанной в прошлом слайде. Обратите внимание, что вам нужны тесты на всё задание, а не только на поле в кавычках.

В классе FieldsParserTask реализуйте метод ParseLine, для которого вы создавали тесты в предыдущей задаче. Создайте модульные тесты на это решение и перенесите разработанные в прошлой задаче тестовые случаи в модульные тесты. Решение получится более простым, если ваши вспомогательные методы будут использовать Token в качестве возвращаемого значения.
