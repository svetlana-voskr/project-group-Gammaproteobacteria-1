# Gammaproteobacteria

## Участники группы
[ФИ] - анализируемый вид с ссылкой на личный репозиторий

+ Енгибарян Нарек - [Erwinia](https://github.com/narek01/hse22_project)
+ Ганецкая Елизавета - [Lysobacter](https://github.com/clumsyred-fox/hse22_project)
+ Таран Юлия - [Halomonas](https://github.com/tomat8jpg/hse2022_project)
+ Гречишкина Полина - [Klebsiella](https://github.com/Monopollia/HSE_project_22_orgs)
+ Чечёкина Ольга - [Aeromonas](https://github.com/OlgaChechekina/Z-DNA_Aeromonas)
+ Бордюгов Максим - [Enterobacter](https://github.com/DedAzaMarks/hse22_project)
+ Шагаева Анна - [Mannheimia](https://github.com/shaggy99999/hse22_project)
+ Меньщиков Дмитрий - [Dickeya](https://github.com/mrGnost/hse22_project)
+ Воскресенская Светлана - [Pseudomonas](https://github.com/svetlana-voskr/hse22_project)
+ Иванова Анна - [Kosakonia](https://github.com/AnnaIvanovaaa/hse22_project)

## Ссылки

[Презентация](https://docs.google.com/presentation/d/1LozU8K9kk02SkZyUv_IBtKXBfuWemxfC3j8vcfUJtqk/edit#slide=id.p)

[Таблица со статистикой]()

## Создание ортологичных кластеров

### *Распределение выбранных кластеров среди родов исследуемых организмов*
![alt](https://github.com/svetlana-voskr/project-group-Gammaproteobacteria-1/blob/lana/pictures/genuses_distribution.png) 

Всего 17076 кластеров. Пиковые значения 10 подтверждают близкое родство анализируемых организмов(родов).

### *Распределение выбранных кластеров среди видов исследуемых организмов*
![alt](https://github.com/svetlana-voskr/project-group-Gammaproteobacteria-1/blob/lana/pictures/species_distribution.png)

Всего 17076 кластеров, видно, что в среднем, кластер включает в себя гены из 25-49 организмов. Пиковые значения в районе 48-49 видов подтверждают близкое родство анализируемых организмов

### *Распределение генов организмов, вошедших в состав кластеров*

Пик количества кластеров приходится на значение 50 генов. Т.к. У нас всего 50 организмов, это связано по большей мере с наличием одного гена от каждого организма в одном кластере. Также наблюдаются высокие количества кластеров, в которые входят гены не из всех организмов (значения меньше 50), при этом наличие более одного гена от одного организма наблюдается значительно реже.

![alt](https://github.com/svetlana-voskr/project-group-Gammaproteobacteria-1/blob/lana/pictures/genes_distribution.png)

### Сводная таблица по выбранным кластерам:

| № | #Species | Genes | Genuses | Genes with Z-DNA | Max ZH-score | Mean ZH-Sqore | Function |
|---|---|---|---|---|---|---|---|
| 977 | 50 | 73 | 10 | 18 | 211093.9 | 35448.16305 | Cysteine desulfurase |
| 1391 | 48 | 69 | 10 | 18 | 23787.35 | 6762.25306667 | Sec-independent protein tranclocase subunit tata |
| 208 | 42 | 67 | 10 | 17 | 29467.88 | 3264.72525882353 | P-ii family nitrogen regulator |
| 481 | 42 | 75 | 10 | 16 | 9852.15 | 2899.2377374999996 | Hth-type transqriptional repressor purr |
| 560 | 49 | 88 | 10 | 15 | 29467.88 | 11363.64275999999 | Lipoprotein-releasing abc transporter permease subunit lole |
| 125 | 44 | 61 | 10 | 14 | 28780.5 | 5917.269785714286 | Pts phossphocarrier protien npr |

Как уже было сказано, всего выделилось 17076 кластеров, из которых были отобраны 7 для дальнейшего анализа. Отбор производился по отсечке на наибольшее количество генов, содержащих З-ДНК

## Создание heatmap

По у-оси представлены геномы, входящие в состав кластеров.
По х-оси - номер кластера, которые были выбраны по наибольшему количеству генов, в которых есть z-днк (7 шт.)

![alt](https://github.com/svetlana-voskr/project-group-Gammaproteobacteria-1/blob/lana/pictures/heatmap_with_annotation.png)

### Дополнительная информация по кластеру 4:

#### Визуализация расположения участков Z-DNA

![alt](https://github.com/svetlana-voskr/project-group-Gammaproteobacteria-1/blob/lana/pictures/Cluster_and_zdna.png)

Наибольшая вероятность формирования Z-формы характерна для участков ДНК, состоящих из повторов вида GC, а в области участков с большим содержанием TA существенно ниже.
Поскольку Z-ДНК не взаимодействует с нуклеосомами, она остается свободным участком в промоторе, с которым могут связываться транскрипционные факторы. 
Функциональная связь Z-ДНК с сигнальными путями интерферона свидетельствует, что Z-ДНК имеет отношение к развитию некоторых заболеваний, как минимум, воспалительного характера. Действительно, к настоящему моменту Z-ДНК уже смогли связать с рядом заболеваний человека.

#### Нуклеотидное выравнивание 

![alt](https://github.com/svetlana-voskr/project-group-Gammaproteobacteria-1/blob/lana/pictures/cluster_4_na.png)

Представлена одна из консервативных областей нуклеотидное выравнивание.
Сходство первичных структур наших последовательностей может отражать их эволюционные взаимосвязи. Есть консервативная область с наибольшим количеством сходств.

#### Аминокислотное выравнивание

![alt](https://github.com/svetlana-voskr/project-group-Gammaproteobacteria-1/blob/lana/pictures/cluster_4_protein.png)

Графическое представление максимально ориентированно на визуальное восприятие. В нём принято размещать последовательности одну под другой, но значение связи между аминокислотами из разных последовательностей обозначаются цветом. Есть окраски по свойствам аминокислот, такие как «Zappo», окрашивающая каждую аминокислоту

## Выводы

1) Род Mannheimia практически не имеет ортологичных генов в выбранных клатерах
2) Роды Pseudomonas и Halomonas имеют очень низкое значение ZH-score для ортологичных последовательностей в выбранных кластерах
3) АА выравнивание подтверждает схожесть белков среди данных родов
4) НТ выравнивание участков Z-DNA показывает относительную консервативность данных последовательностей в ортологичных генах
5) Участки Z-DNA имеют богатый GC состав и могут находиться в промоторных областях





