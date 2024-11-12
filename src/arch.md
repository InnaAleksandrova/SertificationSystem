## Архитектурный стиль

На начальном этапе для упрощения и ускорения разработки и эксплуатации для MVP применять **модульный монолит**. В качестве целевого архитектурного стиля принять микросервисы. 

Логически система должна быть разделена на модули с независимыми БД/схемами и с возможностью последующего выделения микросервисов из производственной части системы.

## Обоснование выбора архитектурного стиля

1. На старте проекта команда разработки не будет превышать 5 разработчиков.

2. Особо строгие нефункциональные требования (по производительности, масштабируемости, надёжности и т.д.) отсутствуют.

3. Инфраструктурная сложность не должна быть избыточной.

4. Ожидается, что требования к системе могут быть пересмотрены после первых релизов, так как бизнес-процесс будет отлаживаться параллельно с внедрением системы. 

5. Если система успешно покажет себя в эксплуатации на примере сертификации одного вида минералов, система будет активно расширяться и дополняться сертификацией других видов образцов. 