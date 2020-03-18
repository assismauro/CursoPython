### Curso de Python do Maurão
    
##### Instruções para seguir os exercícios do curso:

**a)** Instale o [Anaconda](https://www.anaconda.com/distribution/). Para isso primeiro faça o download da versão adequada. Se o seu computador é Windows, a versão é a **Python 3.7 version**, clicando no botão verde, **Download**.

Após o download, também no caso da versão Windows, clique com o botão direito no arquivo baixado e selecione a opção **Executar como administrador**. Siga a instruções do instalador.

**b)** Faça o download dos [dados usados no curso](https://drive.google.com/open?id=15f1t4fGEFA7ZK_N2S_4rse-T-IGg_xjV)

**c)** Descompacte em um diretório **CursoPython\\Data**

**d)** Abra os arquivos [Aula1](https://github.com/assismauro/CursoPython/blob/master/aula1.ipynb), [Aula2](https://github.com/assismauro/CursoPython/blob/master/aula2.ipynb) e [Offtopic](https://github.com/assismauro/CursoPython/blob/master/offtopic.ipynb) e salve-os no diretório **CursoPython\\Aulas** com a extensão **.ypnb**.

Como fazer: Clique [aqui](https://github.com/assismauro/CursoPython/archive/master.zip). Se não der certo, clique no botão verde **Clone or Download** acima, à direita, e em seguida selecione a opção **Download ZIP**. 

Ele vai baixar um arquivo chamado CursoPython-master.zip. Copie o conteúdo desse arquivo para o diretório **CursoPython\\Aulas**.

**e)** Abra o **Anaconda Prompt** (clique no ícone do Windows e pesquise o nome).

**f)** Na janela aberta, digite **cd** <nome completo do diretório CursoPython que vc criou, ex: **c:\\CursoPython** [enter]

**g)** Digite  **jupyter lab --notebook-dir .** [enter] 

**h)** Vá lendo as instruções, quando achar uma célula de contém código, por exemplo:

```python
import pandas

from pandas.plotting import scatter_matrix
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn import model_selection
from sklearn.metrics import classification_report
```
Selecione-a e aperte \<Shift>+\<Enter>. O código será executado. Observe o sinal **[ ]** à esquerda da célula: durante a execução ele aparecerá como **[*]** e após ele aparecerá como **[n]**, onde **n** é o número da célula em ordem de execução.

Espere terminar a execução de uma célula para executar a próxima. Sempre as execute em sequência.

**Observação:** O arquivo [offtopic](https://github.com/assismauro/CursoPython/blob/master/offtopic.ipynb) contém outras informações interessantes sobre o uso do Python em Data Science.
