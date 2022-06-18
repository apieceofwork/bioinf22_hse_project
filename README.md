# Отчёт:

Cсылка на [Colab](https://colab.research.google.com/drive/1qeM2XAs3un_a_sAWs7fR3jrOky-4iCka?usp=sharing)

## 1) Анализ выбранных геномов

* Leishmania orientalis - GCA_000234665
* Leishmania sp. Namibia - GCA_009731335
* Leishmania sp. Ghana 2012 LV757 - GCA_017916335
* Leishmania mexicana MHOM/GT/2001/U1103 - GCA_017918215
* Leishmania tarentolae - 'GCA_017918225

*Эти таблицы есть в колабе, но здесь я их лучше оформила*

Name | Level |  Scaffolds number | GC content
---|---|---|---
 Leishmania orientalis | chromosome | 98| 59.7148
 Leishmania sp. Namibia | chromosome | 67 | 59.5338 
 Leishmania sp. Ghana | chromosome | 116 | 59,6694
 Leishmania mexicana | chromosome | 588 | 59.7793
 Leishmania tarentolae | contig | 179 | 57.4

*Статистика количества генов, длины генома, длины участков экзонами и доли их покрытия*

<img width="827" alt="Screenshot 2022-06-17 at 15 23 17" src="https://user-images.githubusercontent.com/57996343/174297401-602ef567-005d-4b30-911b-d8d88a497624.png">

## Предсказываем z-dna с помощью z-hunt

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

*Ассоциируем предсказанные участки Z-DNA с промотерами генов*

Визуализация 1 участка Z-DNA для 3 генов из генома.

 1) Leishmania orientalis
 
<img width="1232" alt="Screenshot 2022-06-17 at 15 50 42" src="https://user-images.githubusercontent.com/57996343/174301727-82d7df59-5e72-4c2f-b942-82b8ca43d048.png">


2) Leishmania sp. Namibia

<img width="1116" alt="Screenshot 2022-06-17 at 15 50 22" src="https://user-images.githubusercontent.com/57996343/174301666-cc5200b4-8c09-4694-b221-b62f95256560.png">



3) Leishmania sp. Ghana

<img width="1132" alt="Screenshot 2022-06-17 at 15 49 58" src="https://user-images.githubusercontent.com/57996343/174301612-ae9285f7-6592-4358-9e24-191aa343f1cf.png">


4) Leishmania mexicana

<img width="1232" alt="Screenshot 2022-06-17 at 15 49 13" src="https://user-images.githubusercontent.com/57996343/174301494-f367f34e-108a-4e92-8662-2af235032657.png">

5) Leishmania tarentolae

<img width="1232" alt="Screenshot 2022-06-17 at 15 48 35" src="https://user-images.githubusercontent.com/57996343/174301396-ace68fe5-730e-4765-9709-7130003ff943.png">


## 2) Информация по полученным гомологичным кластерам (сколько всего кластеров + гистограмма кластеров по кол-ву разных геномов в кластере - 5, 4, 3, 2)

Общее кол-во кластеров: 8151

**Гистограмма кластеров по кол-ву разных геномов в кластере**

<img width="753" alt="Screenshot 2022-06-17 at 12 34 21" src="https://user-images.githubusercontent.com/57996343/174271534-2d307b31-bf5f-4719-9348-c3b1328b101d.png">


## 3)Таблица с информацией по выбранным кластерам 

## 4) Множественное белковое выравнивание для каждого выбранного кластера 

Выравнивание выполнялось на [сайте:](https://www.ebi.ac.uk/Tools/msa/clustalo/)

Все файлы с выравниваниями можно найти в папке alignments, для выравнивания использовался алгоритм Сlustalw, так он как относительно быстро работает.


## 5) Визуализация расположения участков Z-DNA для каждого выбранного кластера

**Кластер №1**

<img width="491" alt="Screenshot 2022-06-18 at 22 11 09" src="https://user-images.githubusercontent.com/57996343/174453066-86b18c99-a88e-4116-9f57-45b894b8b20f.png">

<img width="491" alt="Screenshot 2022-06-18 at 22 10 25" src="https://user-images.githubusercontent.com/57996343/174453085-5978460c-daaa-40e8-bbce-d1ed7f56f984.png">

<img width="491" alt="Screenshot 2022-06-18 at 22 10 46" src="https://user-images.githubusercontent.com/57996343/174453086-44c69bbb-1bdd-4937-9bda-9cffe81bc70c.png">

<img width="491" alt="Screenshot 2022-06-18 at 22 10 08" src="https://user-images.githubusercontent.com/57996343/174453094-984e25e0-8b7e-4c2f-8f2a-1d87a097308a.png">


<img width="491" alt="Screenshot 2022-06-18 at 22 10 57" src="https://user-images.githubusercontent.com/57996343/174453101-60fff4c2-b886-4e79-99a8-258dd3d8173a.png">


**Кластер №2**

<img width="491" alt="Screenshot 2022-06-18 at 22 14 51" src="https://user-images.githubusercontent.com/57996343/174453178-73381fe7-aae4-4b37-b9b0-aeb9e0e176ac.png">

<img width="491" alt="Screenshot 2022-06-18 at 22 15 04" src="https://user-images.githubusercontent.com/57996343/174453185-084a0123-edb6-4240-976a-963a9c0fd70f.png">

<img width="491" alt="Screenshot 2022-06-18 at 22 14 27" src="https://user-images.githubusercontent.com/57996343/174453193-d4742375-f49a-4d5d-a296-0b842939626a.png">

<img width="491" alt="Screenshot 2022-06-18 at 22 14 39" src="https://user-images.githubusercontent.com/57996343/174453200-19f8f65f-9956-4093-997a-07601ed0b54d.png">

<img width="491" alt="Screenshot 2022-06-18 at 22 15 20" src="https://user-images.githubusercontent.com/57996343/174453205-1746d662-e014-448f-9c94-d365d24ee3f6.png">

**Кластер №3**

<img width="491" alt="Screenshot 2022-06-18 at 22 23 51" src="https://user-images.githubusercontent.com/57996343/174454420-38c28fea-6c25-4bae-a988-ef2e1b5c98b1.png">

<img width="491" alt="Screenshot 2022-06-18 at 22 23 40" src="https://user-images.githubusercontent.com/57996343/174454427-5750dd9a-8c3e-4f03-9f00-bad4cf4056a9.png">

<img width="491" alt="Screenshot 2022-06-18 at 22 23 59" src="https://user-images.githubusercontent.com/57996343/174454436-2660848d-b078-41f1-8fe0-f9bd053cf818.png">

<img width="491" alt="Screenshot 2022-06-18 at 22 24 07" src="https://user-images.githubusercontent.com/57996343/174454437-1cac1b35-68b9-4a1b-8023-7b65538ee0d7.png">

<img width="491" alt="Screenshot 2022-06-18 at 22 24 15" src="https://user-images.githubusercontent.com/57996343/174454448-ea8238bf-e326-43a9-ba61-15495a6edecb.png">

**Кластер №4**

<img width="491" alt="Screenshot 2022-06-18 at 22 26 28" src="https://user-images.githubusercontent.com/57996343/174454508-d526ac15-b76f-4509-9c26-f949ee75f297.png">

<img width="491" alt="Screenshot 2022-06-18 at 22 26 35" src="https://user-images.githubusercontent.com/57996343/174454515-ef4c13b7-5715-416e-9cc0-7512329a7b56.png">

<img width="491" alt="Screenshot 2022-06-18 at 22 26 44" src="https://user-images.githubusercontent.com/57996343/174454522-4f17b193-d0d2-4843-b91f-73a83a23a395.png">

<img width="491" alt="Screenshot 2022-06-18 at 22 26 20" src="https://user-images.githubusercontent.com/57996343/174454526-4f7e83c0-bd0b-48bd-8260-928c14bd2862.png">

<img width="491" alt="Screenshot 2022-06-18 at 22 26 11" src="https://user-images.githubusercontent.com/57996343/174454534-e64f65bf-f96f-49e0-8780-4faef58f2d4e.png">

**Кластер №5**

<img width="491" alt="Screenshot 2022-06-18 at 22 30 11" src="https://user-images.githubusercontent.com/57996343/174454608-8891cad2-74f9-4fae-8bb9-22a4a8990597.png">

<img width="497" alt="Screenshot 2022-06-18 at 22 30 03" src="https://user-images.githubusercontent.com/57996343/174454613-7329fe1d-8fba-4a30-abb0-74dbbe36e87d.png">

<img width="491" alt="Screenshot 2022-06-18 at 22 29 55" src="https://user-images.githubusercontent.com/57996343/174454617-d009fc4d-b35f-4b49-8cc6-512ba5acc7c2.png">

<img width="491" alt="Screenshot 2022-06-18 at 22 29 36" src="https://user-images.githubusercontent.com/57996343/174454621-df40a818-6831-42c0-8df6-a8910d65df66.png">

<img width="491" alt="Screenshot 2022-06-18 at 22 29 46" src="https://user-images.githubusercontent.com/57996343/174454624-24bcac8b-c562-44a4-a834-a786e42f3a60.png">



