# Counting_of_cells
Наш проект подразумевает создание биосовместимых электропроводящих скаффолдов (каркасов) для регенерации тканей сердца. Один из этапов подразумевает дифференцировку стволовых клеток, а также оптимизацию методик их выращивания (изменения состава среды, реагентов, концентраций и т.д.). Для анализа роста клеток и их количества необходимо считать их вручную или с помощью дорогостоящих приборов. Чтобы упростить и автоматизировать данный процесс, мы написали скрипт для подсчета процентного соотношения площади живых клеток на основе изображений окрашенных клеток в двух цветовых каналах: синем со всеми клетками и красном с мертвыми клетками.<br>
Также мы собрали базу данных с этими изображениями для обучения нейросети, если в дальнейшем нам понадобится более высокая точность подсчета.
Пример изображений:<br>
![Image](/images/8_2_all.png)
![Image](/images/8_2_dead.png)
