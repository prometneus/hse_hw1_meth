# hse_hw1_meth

## [Colab](https://colab.research.google.com/drive/124uWf5F4w3LDTYR2owhtsqxD0teZtN3X?usp=sharing)

## Особенности секвенирования РНК по сравнению с ДНК

В первую очередь, что бросается в глаза -- так это крайне необычный вид графика GC-content -- он больше никаким образом не похож на график нормального распределения. Наблюдаются два пика на позициях приблизительно 22% и 70%. 

![image](https://user-images.githubusercontent.com/86663451/154715666-dd6830eb-2b6d-4b66-afa0-c079efa8cf6c.png)

Также заметно отличие на графике Per base sequence content: много тимина и мало цитозина по сравнению с тем же графиком секвенированной ДНК.

![image](https://user-images.githubusercontent.com/86663451/154717786-5e549902-d353-434e-8030-e7d0439db1fa.png)

Это может быть объяснено фактом бисульфитного секвенирования: при воздействии бисульфитом на ДНК, цитозин превращается в урацил, но не весь, ведь если цитозин метилирован, он не подвергается превращению. Но это ДНК, поэтому урацил считывается как тимин


## Число ридов, картированных на участки, и процент дупликации
Стадия развития |	Название |	Риды на участке 11347700-11367700 |	Риды на участке 40185800-40195800 | Процент дуплицирования 
-|-|-|-|-
8cell |	SRR5836473 |	1090 | 464 | 18.31% 
Epiblast |	SRR3824222 |	2328 |	1062 | 2.92% 
ICM |	SRR5836475|	1456 |	630 | 9.08% 

## M-Bias графики
8 cell |	Epiblast | ICM
-|-|-
![image](pics/8cell1.png) |	![image](pics/epiblast1.png) |	![image](pics/icm1.png)
![image](pics/8cell2.png) |	![image](pics/epiblast2.png) |	![image](pics/icm2.png)

## Гистограммы распределения метилирования цитозинов по хромосоме
8 cell |	Epiblast | ICM
-|-|-
![image](pics/8cell_hist.png) |	![image](pics/Epiblast_hist.png) |	![image](pics/ICM_hist.png)

## Графики покрытия и метилирования
![image](pics/image_cov.png)

![image](pics/another_image_cov.png)
