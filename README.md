# hse22_project
[Colab](https://colab.research.google.com/drive/1SPWmm93CB1xDCDNlrCyG0X02PYsMQ7Sr?usp=sharing)

Выбранные геномы:
- Porcisia hertigi (GC = 56,0229%)
- Trypanosoma melophagium (GC = 41,2%)
- Leishmania sp. Namibia (GC = 59,5338%)
- Trypanosoma vivax (GC = 53,6%)
- Trypanosoma theileri (GC = 41,4%)
## Анализ аннотированных генов
Название |Число генов	| Длина генома	| Длина участков с экзонами	| Процент покрытия |
| ------------- | :-------------: |------------:| -----------:|-----------:|
Leishmania|	8266.0	|34118624.0	|15856612.0|	46.0
Porcisia_hertigi|	7891.0|	34958538.0|	15049088.0	|43.0
Trypanosoma_theileri|	11312.0|	29822211.0|	16317987.0	|55.0
Trypanosoma_melophagium|	9768.0|	23303718.0|	15571565.0	|67.0
Trypanosoma_vivax	|17806.0|	67823889.0|	19237085.0	|28.0

## Предсказание Z-DNA
|   Название              |   Кол-во предсказанных участков |   Общая длина участков |   Участки, где zh-score > 500 |
|:------------------------|--------------------------------:|-----------------------:|------------------------------:|
| Leishmania sp. Namibia  |                          319787 |                  96572 |                          9044 |
| Porcisia_hertigi        |                          258204 |                  54572 |                          4946 |
| Trypanosoma_theileri    |                           30147 |                   1098 |                            97 |
| Trypanosoma_melophagium |                          117947 |                   3584 |                           340 |
| Trypanosoma_vivax       |                           30462 |                   6994 |                           687 |

## Гистограммы

![Снимок экрана 2022-06-13 в 11 09 01](https://user-images.githubusercontent.com/32986053/173308837-a75e888e-fe7d-4c09-97a8-9dc9b5b84eef.png)
![Снимок экрана 2022-06-13 в 11 09 24](https://user-images.githubusercontent.com/32986053/173308907-9206a122-a8ba-4e8a-9561-802c3a47c1f1.png)
![Снимок экрана 2022-06-13 в 11 09 47](https://user-images.githubusercontent.com/32986053/173308963-d686c252-7c19-481b-b6e2-78a1e57bd094.png)
![Снимок экрана 2022-06-13 в 11 10 06](https://user-images.githubusercontent.com/32986053/173309031-3e680143-7665-4f99-82b3-236dece395b6.png)
![Снимок экрана 2022-06-13 в 11 10 23](https://user-images.githubusercontent.com/32986053/173309085-af44969b-939f-43ee-a659-ee422a34d3b3.png)

## Ассоциируем предсказанные участки Z-DNA с промотерами генов
|  Название               |       Картинка                  |
|:------------------------|--------------------------------:|
|Leishmania sp. Namibia | ![Снимок экрана 2022-06-13 в 16 52 02](https://user-images.githubusercontent.com/32986053/173368951-1406ee9a-9071-4c3c-a3d9-e49086c35697.png)|
|Porcisia_hertigi|![Снимок экрана 2022-06-13 в 16 55 04](https://user-images.githubusercontent.com/32986053/173369607-2926523a-186b-4959-bda3-299dbb5a817d.png)|
|Trypanosoma_theileri|![Снимок экрана 2022-06-13 в 16 57 19](https://user-images.githubusercontent.com/32986053/173370046-120bfad2-1126-461b-aa54-95242e114aae.png)|
|Trypanosoma_melophagium|![Снимок экрана 2022-06-13 в 16 54 20](https://user-images.githubusercontent.com/32986053/173369455-95ec95aa-575b-4f0a-9155-ae67516d1082.png)|
|Trypanosoma_vivax |![Снимок экрана 2022-06-13 в 16 57 49](https://user-images.githubusercontent.com/32986053/173370160-10588d3f-f33b-4145-977c-2968262629ff.png)

## Гомологичные связи между белками выбранных геномов, выбор кластеров
![Снимок экрана 2022-06-14 в 20 16 39](https://user-images.githubusercontent.com/32986053/173637757-04088d12-3ca3-496e-80ad-6be9a65eb601.png)
## Таблица по кластерам
|      |   # Species |   Genes |   Alg.-Conn. | Leishmania.faa   | Porcisia_hertigi.faa   | Trypanosoma_melophagium.faa   | Trypanosoma_theileri.faa   | Trypanosoma_vivax.faa   |
|-----:|------------:|--------:|-------------:|:-----------------|:-----------------------|:------------------------------|:---------------------------|:------------------------|
| 2024 |           5 |       5 |       0.77   | KAG5503124.1     | KAG5507102.1           | KAH9589123.1                  | ORC92364.1                 | KAH8610918.1            |
| 3525 |           5 |       5 |       0.195  | KAG5502702.1     | KAG5506524.1           | KAH9601285.1                  | ORC88912.1                 | KAH8612542.1            |
| 2482 |           5 |       5 |       0.668  | KAG5494665.1     | KAG5496182.1           | KAH9578681.1                  | ORC88369.1                 | KAH8603519.1            |
|  817 |           5 |       5 |       0.861  | KAG5493714.1     | KAG5495256.1           | KAH9588995.1                  | ORC87231.1                 | KAH8617371.1            |
| 1985 |           5 |       5 |       0.776  | KAG5490891.1     | KAG5492435.1           | KAH9597366.1                  | ORC84722.1                 | KAH8607800.1            |
|  947 |           5 |       5 |       0.85   | KAG5488901.1     | KAG5490630.1           | KAH9577996.1                  | ORC90411.1                 | KAH8620693.1            |
| 1069 |           5 |       5 |       0.842  | KAG5491322.1     | KAG5492838.1           | KAH9601491.1                  | ORC92044.1                 | KAH8604232.1            |
|  576 |           5 |       5 |       0.89   | KAG5494779.1     | KAG5496284.1           | KAH9578758.1                  | ORC88239.1                 | KAH8605008.1            |
| 3657 |           5 |       5 |       0.0997 | KAG5500782.1     | KAG5503477.1           | KAH9597250.1                  | ORC88762.1                 | KAH8605933.1            |
| 2183 |           5 |       5 |       0.74   | KAG5507153.1     | KAG5510891.1           | KAH9599938.1                  | ORC86514.1                 | KAH8614023.1            |
## Функции генов
|       | product_accession   | name                 |
|------:|:--------------------|:---------------------|
|  2075 | KAG5507153.1        | hypothetical protein |
|  7676 | KAG5503124.1        | hypothetical protein |
|  8189 | KAG5502702.1        | hypothetical protein |
| 10487 | KAG5500782.1        | hypothetical protein |
| 17645 | KAG5494665.1        | hypothetical protein |
| 17987 | KAG5494779.1        | hypothetical protein |
| 19415 | KAG5493714.1        | hypothetical protein |
| 20894 | KAG5490891.1        | hypothetical protein |
| 22187 | KAG5491322.1        | hypothetical protein |
| 24059 | KAG5488901.1        | hypothetical protein |

|       | product_accession   | name                 |
|------:|:--------------------|:---------------------|
|  1865 | KAG5510891.1        | hypothetical protein |
|  6980 | KAG5507102.1        | hypothetical protein |
|  7514 | KAG5506524.1        | hypothetical protein |
|  9563 | KAG5503477.1        | hypothetical protein |
| 15671 | KAG5496182.1        | hypothetical protein |
| 15977 | KAG5496284.1        | hypothetical protein |
| 17393 | KAG5495256.1        | hypothetical protein |
| 18779 | KAG5492435.1        | hypothetical protein |
| 19988 | KAG5492838.1        | hypothetical protein |
| 22754 | KAG5490630.1        | hypothetical protein |

|       | product_accession   | name                                                                |
|------:|:--------------------|:--------------------------------------------------------------------|
|  3902 | ORC88912.1          | putative separase, putative,cysteine peptidase, Clan CD, family C50 |
|  4805 | ORC88762.1          | hypothetical protein                                                |
|  5948 | ORC88239.1          | ATP-dependent RNA helicase                                          |
|  6338 | ORC88369.1          | hypothetical protein                                                |
| 11840 | ORC87231.1          | GTP-binding elongation factor Tu family                             |
| 13577 | ORC86514.1          | hypothetical protein                                                |
| 20186 | ORC92364.1          | hypothetical protein                                                |
| 22244 | ORC84722.1          | ubiquinol-cytochrome c reductase subunit 7                          |
| 24386 | ORC92044.1          | hypothetical protein                                                |
| 32033 | ORC90411.1          | phosphatidylinositol glycan, class P                                |

|       | product_accession   | name                                    |
|------:|:--------------------|:----------------------------------------|
|    56 | KAH9601285.1        | hypothetical protein                    |
|  3828 | KAH9599938.1        | ER membrane protein complex subunit 8/9 |
|  7088 | KAH9601491.1        | Protein of unknown function DUF2009     |
| 11543 | KAH9597366.1        | Cytochrome b-c1 complex subunit 7       |
| 12525 | KAH9597250.1        | IQ motif                                |
| 16472 | KAH9588995.1        | Transcription factor                    |
| 21813 | KAH9589123.1        | PIH1                                    |
| 25160 | KAH9578681.1        | hypothetical protein                    |
| 25558 | KAH9578758.1        | DEAD/DEAH box helicase domain           |
| 26914 | KAH9577996.1        | PIG-P                                   |

|       | product_accession   | name                                                           |
|------:|:--------------------|:---------------------------------------------------------------|
|   857 | KAH8620693.1        | putative PIG P                                                 |
| 10715 | KAH8617371.1        | Elongation factor Tu GTP binding domain                        |
| 21455 | KAH8614023.1        | putative Uncharacterized protein family (UPF0172)              |
| 25388 | KAH8612542.1        | putative cysteine peptidase Clan CD family C50                 |
| 30551 | KAH8610918.1        | putative pre RNA processing PIH1 Nop17                         |
| 38609 | KAH8607800.1        | putative Ubiquinol cytochrome C reductase complex 14kD subunit |
| 45158 | KAH8605933.1        | hypothetical protein                                           |
| 47435 | KAH8605008.1        | DEAD DEAH box helicase Helicase conserved C terminal domain    |
| 50180 | KAH8604232.1        | putative Protein of unknown function (DUF2009)                 |
| 52685 | KAH8603519.1        | hypothetical protein                                           |
