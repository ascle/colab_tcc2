# Etapas de um projeto de aprendizado de máquina

1) Abordar o problema e analisar o panorama em geral;
2) Obter os dados;
   
	**2_conhecendo_dados.ipynb**
3) Explorar os dados para obter informações úteis;

	**2_conhecendo_dados.ipynb**
   
	**4_analise_exploratoria.ipynb**
5) Preparar os dados para melhor expor os padrões de dados subjacentes aos algoritmos do Aprendizado de Máquina;

	**3_limpeza-tratamento_dos_dados.ipynb**
6) Explorar vários modelos diferentes e liste os melhores;
   
	**5_modelagem-classificacao_1.ipynb**
   
	**5_modelagem-classificacao_2.ipynb**
8) Ajustar seus modelos e combine-os em uma ótima solução;
    
	**5_modelagem-classificacao_3.ipynb**
9) Apresentar sua solução;
10) Implementar, monitorar e fazer a manutenção de seu sistema.

# Códigos fonte

Ler base de dados a partir de um upload de arquivo:
```python
import pandas as pd
dados = pd.read_csv('dn.csv')
dados.head()
```

Ler base de dados armazenada no Google Drive, será necessário confirmar permissão no pop-up.
```python
from google.colab import drive
from os import chdir

drive.mount('/content/drive', force_remount=True)
chdir('/content/drive/MyDrive/')
```
