# Предварительный анализ данных Hi-C, включающий кластеризацию реплик.

## [Google-collab](https://colab.research.google.com/drive/1AON5G0bY9wnEFfA9njXUY1FdLZDwmSsn?usp=sharing)

## Построение графика скейлинга для одного из образцов в логарифмических координатах 

<img width="573" alt="Снимок экрана 2023-05-09 в 19 28 48" src="https://github.com/sonishko/hse_hw4_HiC/assets/99287058/a2488935-25a8-4f09-8b19-b8dab2aec83c">

График скейлинга строится для каждой отдельной хромосомы. В моем случае я строила график скейлинга для X-хромосомы второго образца клеточной линии bg3 (нервная ткань дрозофиллы). На полученном графике видна зависимость частоты возниконовения контактов в зависимости от расстояния между этими участками: чем больше расстояние между участками, тем ниже частота их взаимодействий. 


## Построение дендрограммы реплик  Hi-C для клеточных линий дрозофилы bg3 (нервная ткань) и kc167 (эмбриональная линия) на основе коэффициента SCC

<img width="701" alt="Снимок экрана 2023-05-09 в 19 35 39" src="https://github.com/sonishko/hse_hw4_HiC/assets/99287058/8fe2ce08-749c-40ed-8cd0-c85f52a4c00e">

Дендрограмма отлично подтверждает, что образцы относящиеся к одному типу тканей намного больше похожи друг на друга, чем образцы разных типов тканей. При этом образцы нервной ткани чуть больше похожи между собой, чем образцы эмбриональной.

Таким образом мы показали, что используемые образцы подходят для анализа HiC, разница в структуре хроматина НЕ может быть расценена как случайный результат вследствие сильного разброса данных.

