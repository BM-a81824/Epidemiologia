# SIG - Final Project 

No âmbito da Unidade Curricula de Sistema de Informação Geográfica foi solicitado um projeto que envolvesse a manipulação e tratamento de dados relacionados com o vírus COVID-19. No presente trabalho foram tratados e manipulados dados nas ferramentas QGIS e Jupyter (PyQGIS) e também realizada a extração de dados provindas de bases de dados.

Abaixo segue-se a estruturação do trabalho, bem como o que cada parte inclui.


## Organização da pasta:
  * [Countries](https://github.com/BM-a81824/Epidemiologia/tree/master/SIG-FinalProject/Countries): layers utilizadas para criar os mapa mundo;
  * [Covid19](https://github.com/BM-a81824/Epidemiologia/tree/master/SIG-FinalProject/Covid19): dados relativos à doença, retirados do repositório [COVID-19](https://github.com/CSSEGISandData/COVID-19)
  * [Geopackages](https://github.com/BM-a81824/Epidemiologia/tree/master/SIG-FinalProject/Geopackages): dados relativos a Portugal do repositório [covid-pt](https://github.com/jgrocha/covid-pt)


## Organização da informação (ficheiro ipynb): 

### FinalProject-PT: 
* Construção de mapas por concelho e por distrito dos casos em Portugal:
 ![Concelho](https://github.com/BM-a81824/Epidemiologia/blob/master/SIG-FinalProject/Figures/Portugal/MapaPortugalConcelhos.png)
 ![Distrito](https://github.com/BM-a81824/Epidemiologia/blob/master/SIG-FinalProject/Figures/Portugal/MapaPortugalDistritos.png)

* Construção de gráficos barras, circulares com e sem legenda das localidades com mais de 500 casos, quer para concelhos como para os distritos. De seguida, apresentam-se os dos concelhos:
![Bar Chart](https://github.com/BM-a81824/Epidemiologia/blob/master/SIG-FinalProject/Figures/Portugal/barConcelho500.png)
![Pie Chart](https://github.com/BM-a81824/Epidemiologia/blob/master/SIG-FinalProject/Figures/Portugal/pieConcelho500.png)
![Pie Chart legend](https://github.com/BM-a81824/Epidemiologia/blob/master/SIG-FinalProject/Figures/Portugal/pie_legConcelho500.png)


Relativamente à informação mundial foram estudados os casos de confirmados, mortos e recuperados por meio de mapas e gráficos estatísticos.

### [FinalProject-WW_maps](https://github.com/BM-a81824/Epidemiologia/blob/master/SIG-FinalProject/FinalProject-WW_maps.ipynb):

![Mapa Taxa Mortalidade](https://github.com/BM-a81824/Epidemiologia/blob/master/SIG-FinalProject/Figures/WW/Mortalidade.png)
![Mapa Taxa Recuperados](https://github.com/BM-a81824/Epidemiologia/blob/master/SIG-FinalProject/Figures/WW/Recuperados.png)
![Mapa Taxa Recuperados por morte](https://github.com/BM-a81824/Epidemiologia/blob/master/SIG-FinalProject/Figures/WW/Recuperados_morte.png)

### [FinalProject-WW_stats](https://github.com/BM-a81824/Epidemiologia/blob/master/SIG-FinalProject/FinalProject-WW_stats.ipynb)

