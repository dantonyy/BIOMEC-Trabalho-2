# BIOMEC Trabalho 2
# Dantony Donato - 11845581

Passo a passo para realização do trabalho proposto:

	Passo 1: Clonar repositório IBmBiomec2021 para máquina pessoal
	Passo 2: Criou-se o repositório BIOMEC-Trabalho-2 e copiou-se os arquivos da pasta Encontro04 para este novo repositório.
	Passo 3: Primeira tentativa de rodar o comando "python kvelball.py c1.txt c2.txt c1cal.txt c2cal.txt calibrador_ref.txt resultado" no GitBash
		Problema 1: Encontrei problemas na utilização do comando acima, como a falta das bibliotecas numpy, pandas, scipy e matplotlib, para isso, 
		usei o comando "pip install <biblioteca>" no CMD do windows para instalar cada uma das bibliotecas que estavam em falta.
		Problema 2: Erros de syntax na utilização do comando "pip install" que foram resolvidos adicionando a pasta do python, python/scripts ao path do windows.
	Passo 4: Com os problemas acima resolvidos, utilizou-se novamente o comando "python kvelball.py c1.txt c2.txt c1cal.txt c2cal.txt calibrador_ref.txt resultado" no GitBash
	e como resultado, os gráficos foram mostrados na tela e gerou-se 3 arquivos na pasta Encontro04: 'resultado.3d', 'resultado_filt.3d' e 'resultado_result.txt'