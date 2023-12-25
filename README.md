# GMGC data downloaded from https://gmgc.embl.de

This repository collects Global Microbial Gene Catalog (GMGC) sequence data, which store separately according to sequence length.


## Data statistics

The number of sequences is shown below:

|Length $L$|`Built environment`|`Cat gut`|`Dog gut`|`Freshwater`|`Human gut`|`Human nose`|`Human oral`|`Human skin`|`Human vagina`|`Marine`|`Mouse gut`|`Pig gut`|`Soil`|`Wastewater`|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|$5000 \leq L \leq 10000$ |10423|11694|9221|1853|82549|10786|33935|33167|5261|28914|5222|32600|10568|12775|
|$10000 \leq L \leq 20000$|2263 |922  |859 |488 |8587 |886  |2908 |3987 |330 |3338 |512 |3512 |1306 |1627 |
|$20000 \leq L \leq 30000$|1347 |875  |190 |57  |2128 |996  |1000 |1463 |28  |396  |80  |600  |185  |392  |
|$30000 \leq L \leq 40000$|2149 |1913 |1   |1   |2338 |2187 |1921 |2163 |0   |38   |7   |63   |229  |3    |
|$L \geq 40000$           |11   |1    |0   |0   |122  |68   |0    |51   |0   |6    |11  |2    |9    |2    |


## How to use data

All data in this repository has zipped by `xz`. Use `xz` in unix system to decompress files. 

The folder of datasets is shown below:

|Dataset name|Folder name|
|:-:|:-:|
|`Built environment`|built-env|
|`Cat gut`|cat-gut|
|`Dog gut`|dog-gut|
|`Freshwater`|freshwater|
|`Human gut`|human-gut|
|`Human nose`|human-nose|
|`Human oral`|human-oral|
|`Human skin`|human-skin|
|`Human vagina`|human-vagina|
|`Marine`|marine|
|`Mouse gut`|mouse-gut|
|`Pig gut`|pig-gut|
|`Soil`|soil|
|`Wastewater`|wastewater|


## Ciation

Coelho, L.P., et al. Towards the biogeography of prokaryotic genes. Nature 601, 252–256 (2022).