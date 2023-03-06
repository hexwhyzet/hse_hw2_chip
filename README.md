# Кабаков Иван 1 группа

### Colab
https://colab.research.google.com/drive/13RfNb9PS2f68HAyHRz8PgYrBJCDMhKt0?usp=sharing

#### Ссылка на эксперимент в Encode 
https://www.encodeproject.org/experiments/ENCSR760ZVL/

### Реплика 1 - ENCFF025CYO
### Реплика 2 - ENCFF857ZQN
### Контроль - ENCFF418LZN

## FastQC

### ENCFF025CYO

![ENCFF025CYO_fastq.png](pictures%2FENCFF025CYO_fastq.png)

### ENCFF857ZQN

![ENCFF418LZN_fastq.png](pictures%2FENCFF418LZN_fastq.png)

### ENCFF418LZN

![ENCFF857ZQN_fastq.png](pictures%2FENCFF857ZQN_fastq.png)

В случае контроля стоило сделать подрезание, но я забыл :)

## Выравнивание

| ID | Чтений | НЕ выравнилось | выравнилось уникально | выравнилось НЕ-уникально |
|-|-|-|-|-|
| ENCFF025CYO | 91312067 | 84.96% | 3.09% | 11.95% |
| ENCFF857ZQN | 53170052 | 86.55% | 2.84% | 10.61% |
| ENCFF418LZN | 13562825 | 84.23% | 3.23% | 12.54% |

## Диаграммы пиков

[Intervene_venn.pdf](data%2FIntervene_venn.pdf)

[Intervene_venn-2.pdf](data%2FIntervene_venn-2.pdf)

[Intervene_venn-3.pdf](data%2FIntervene_venn-3.pdf)

[Intervene_venn-4.pdf](data%2FIntervene_venn-4.pdf)

Числа получились небольшие скорее всего всё из-за того, 
что я взял очень маленьку хромосому для выравнинвания chr22. Мы и так
берем одну хромосому, так она еще и очень маленькая.

## Результат Бонуса

Я взял две записи ENCFF783MYB.bigWig и ENCFF502IGF.bigWig, взял сразу bigWig чтобы не мучаться с переводом из bam.

Программа ну очень долга работала... в сумме почти 5 часов...

![result.png](pictures%2Fresult.png)

![result2.png](pictures%2Fresult2.png)
