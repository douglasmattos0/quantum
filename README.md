# quantum
Quantum Machine Learning &amp; AI

Os passos para Instalação do Ambiente de Desenvolvimento Qiskit pode ser encontrado no link abaixo:
https://www.youtube.com/watch?v=dZWz4Gs_BuI&t=78s

Obs.:
1- Instalação do Miniconda
    Conforme passos apresentados no video, pode ser instalado em MacOS, Linux e Windows
    Procedimento padrão, Next, Next, Finish

2- Criar ambiente Virtual Python

(base) D:\workspaces\ws-quantum\quantum>conda create --name env
Channels:
 - defaults
Platform: win-64
Collecting package metadata (repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: C:\Users\dougl\.conda\envs\env



Proceed ([y]/n)? y

Preparing transaction: done
Verifying transaction: done
Executing transaction: done
#
# To activate this environment, use
#
#     $ conda activate env
#
# To deactivate an active environment, use
#
#     $ conda deactivate


(base) D:\workspaces\ws-quantum\quantum>conda activate env

(env) D:\workspaces\ws-quantum\quantum>

3- Instalação do Python Package Manager - pip
(env) D:\workspaces\ws-quantum\quantum> conda install pip

4- Instalação dos pacotes do IBM Qiskit
(env) D:\workspaces\ws-quantum\quantum> pip install qiskit
(env) D:\workspaces\ws-quantum\quantum> pip install matplotlib
(env) D:\workspaces\ws-quantum\quantum> pip install ibm_qiskit_runtime
(env) D:\workspaces\ws-quantum\quantum> pip install pylatexenc