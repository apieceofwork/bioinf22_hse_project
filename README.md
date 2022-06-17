# Отчёт:

Cсылка на [Colab](https://colab.research.google.com/drive/14TCmO1bf1ZrzgHraaVSzhe22rdZqvtzK?usp=sharing)

## 1) Анализ выбранных геномов

* Leishmania orientalis - GCA_000234665
* Leishmania sp. Namibia - GCA_009731335
* Leishmania sp. Ghana 2012 LV757 - GCA_017916335
* Leishmania mexicana MHOM/GT/2001/U1103 - GCA_017918215
* Leishmania tarentolae - 'GCA_017918225

Эти таблицы есть в колабе, но здесь я их лучше оформила

Name | Level |  Scaffolds number | GC content
---|---|---|---
 Leishmania orientalis | chromosome | 98| 59.7148
 Leishmania sp. Namibia | chromosome | 67 | 59.5338 
 Leishmania sp. Ghana | chromosome | 116 | 59,6694
 Leishmania mexicana | chromosome | 588 | 59.7793
 Leishmania tarentolae | contig | 179 | 57.4

Статистика количества генов, длины генома, длины участков экзонами и доли их покрытия

<img width="827" alt="Screenshot 2022-06-17 at 15 23 17" src="https://user-images.githubusercontent.com/57996343/174297401-602ef567-005d-4b30-911b-d8d88a497624.png">

# Предсказываем z-dna с помощью z-hunt

Name | number of sites with zh-score > 500 | overall_seq_length | z-dna predicted sites number
|---|---|---|---
 Leishmania orientalis | 8416.0 | 91030.0 | 273291
 Leishmania sp. Namibia | 9224.0 | 101250.0 | 296165
 Leishmania sp. Ghana | 9141.0 | 97978.0 | 347095
 Leishmania mexicana | 8503.0 | 91738.0 | 295535
 Leishmania tarentolae | 9044.0 | 96572.0 | 319787
 
 Гистограммы значений zh-score
 
 
<img width="594" alt="Screenshot 2022-06-17 at 15 35 55" src="https://user-images.githubusercontent.com/57996343/174299390-83032db6-f7dc-4ce4-8050-31bb0b240438.png">

<img width="596" alt="Screenshot 2022-06-17 at 15 38 56" src="https://user-images.githubusercontent.com/57996343/174299851-7776f677-4cc8-44aa-b8e6-c6f771b7a68a.png">

<img width="593" alt="Screenshot 2022-06-17 at 15 39 14" src="https://user-images.githubusercontent.com/57996343/174299893-ea8db274-49cf-4ac4-bc06-f26f1d180fa1.png">

<img width="592" alt="Screenshot 2022-06-17 at 15 39 36" src="https://user-images.githubusercontent.com/57996343/174299957-774e5400-af0d-45cd-b0b8-931b102ce889.png">

<img width="597" alt="Screenshot 2022-06-17 at 15 39 50" src="https://user-images.githubusercontent.com/57996343/174299990-6735017d-3ccb-4923-abf6-1a6c0f87458d.png">



## 2) Информация по полученным гомологичным кластерам (сколько всего кластеров + гистограмма кластеров по кол-ву разных геномов в кластере - 5, 4, 3, 2)

Общее кол-во кластеров: 8151

**Гистограмма кластеров по кол-ву разных геномов в кластере**

<img width="753" alt="Screenshot 2022-06-17 at 12 34 21" src="https://user-images.githubusercontent.com/57996343/174271534-2d307b31-bf5f-4719-9348-c3b1328b101d.png">



## 3)Таблица с информацией по выбранным кластерам (сколько генов в кластере, функция этих генов, расположение Z-DNA относительно этих генов, Z-DNA score) - не более 10 шт (пока не сделано!)


## 4) Множественное белковое выравнивание для каждого выбранного кластера (пока не сделано)


## 5) Визуализация расположения участков Z-DNA для каждого выбранного кластера


