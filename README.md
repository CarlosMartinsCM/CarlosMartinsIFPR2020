# Ambiente de desenvolvimento WEB II

## Ferramentas para instalação

- Python e Pip
- Pycharm
- Git
- SQLite
- SQLite Browser

---
## Sistema operacional Windows 11

### **Python versão 3.10.2**

Python é uma linguagem de programação de alto-nível, criada em 1989 por
Guido Vam Hossum.  
Caracterisa-se por ser:

- Uma linguagem multiplataforma, o mesmo código se adapta a varios sistemas operacionais.
- Linguagem de proposito geral, usada em varias aplicações e dispositivos.
- Organizada e de fácil leitura do código, exige poucas linhas de código se comparado ao mesmo programa em outras linguagens.
- Orientada a objetos.
- Código aberto.
- Possui varias bibliotecas para uso em várias situações.

_**Instalação:**_

1. Fazer o dowload da linguagem em seu site oficial [Python.org.](https://www.python.org/)  
![Versão Python](https://github.com/CarlosMartinsIFPR2020/imagens/blob/cf58ca729186c71713b980a088d91346bc043b20/python01.png)

2. Escolher a versão a ser instalada, de acordo com o sistema operacional, de preferência optar pela versão mais recente.  
![Versão Python](https://github.com/CarlosMartinsIFPR2020/imagens/blob/6329a0e135f8a18e91fd7b4b1c63569e3190f8ca/python_versao.png)

3. Executar o instalador, seguindo os passos solicitados, marcar a opção ADD PYTHON ("Versão do Python") ao PATH.  
![Versão Python](https://github.com/CarlosMartinsIFPR2020/imagens/blob/d53f33e274b7d28490c4da692f88f172467daf2c/instalador.png)

4. Após isso basta fechar o instalador e o Python estará instalado. É recomendável desabilitar "path lenth limit".
![Versão Python](https://github.com/CarlosMartinsIFPR2020/imagens/blob/a22b29d008d18e305d90991ad2870c3314e848ed/python_finalizado.png)

Para testar, abra o terminal e digite o comando:  
```
python --version  
```
Será mostrado a versão instalada.
![Versão Python](https://github.com/CarlosMartinsIFPR2020/imagens/blob/ce55767aac69b1287d115d16425ec6ac2366e3e7/python_cmd_vers%C3%A3o.png)

### **Pip versão 21.2.4**

Pip trata-se de um sistema gerenciador de pacotes (bibliotecas) que são utilizadas para trazer mais funcionalidade ao Python.  
O Pip contém uma grande infinidade de links e pacotes que derivam da comunidade oficial de desenvolvedores Python, assim não é necessário
acessar o repositório de cada desenvolvedor para se ter acesso ao pacote que se deseja, basta fazer a pesquisa no site oficial [Pypi.org](https://pypi.org/)
e utilizar o Pip para sua integração.

Para testar se o Pip está instalado digite o seguinte comando no terminal:
```
pip --version  
```
Será mostrada a versão instalada.
![Versão Python](https://github.com/CarlosMartinsIFPR2020/imagens/blob/dfbdb589ef385aa32514b35a0752bedb93e85b88/Pip_version.png)

### **PyCharm versão 2021.3.1**

O PyCharm é um IDE (ambiente de desenvolvimento integrado) utilizado para programação em Python, que possui diversos recursos
extremamente úteis e que facilitam as tarefas de desenvolvimento de software principalmente quando comparado com o
IDE padrão do Python, o IDLE.  
O PyCharm é desenvolvido pela empresa JetBrains, sendo escrito em Java e Python, e está disponível para vários
sistemas operacionais, como Windows, Linux e OS X.  

Principais recursos do PyCharm

- Debugger gráfico
- Unidade de testes integrada
- Integração com sistemas de controle de versão, como Git, Mercurial e Subversion
- Análise de código
- Code Completion
- Sintaxe e Erros destacados
- Refatoração
- Suporte a desenvolvimento com Django  

_**Instalação:**_

1. Baixar o software pelo site oficial [JetBrains.com](https://www.jetbrains.com/pt-br/pycharm/download/#section=windows) escolhendo a versão
correspondente ao seu sistema operacional.  
Optar pela versão gratuita.
![Pycharm_version](https://github.com/CarlosMartinsIFPR2020/imagens/blob/20349e99bd7a4e74df2bd5570ede6df180116822/pycharm_download_version.png)  
2. Executar o instalador.  
Marcando a opção Creat Associations .py  
![Pycharm_instalador](https://github.com/CarlosMartinsIFPR2020/imagens/blob/381c1b97c07dd53acda5cf519982589cd3814dde/pycharm_instalador_inicio.png)  
3. Clicar em install.  
![Pycharm_processo](https://github.com/CarlosMartinsIFPR2020/imagens/blob/381c1b97c07dd53acda5cf519982589cd3814dde/pycharm_instalador_processo.png)  
4. Processo finalizado, clicar em Finish.  
![Pycharm_processo](https://github.com/CarlosMartinsIFPR2020/imagens/blob/381c1b97c07dd53acda5cf519982589cd3814dde/pycharm_instalador_finalizado.png)  
IDE instalada  
![Pycharm_tela_inicial](https://github.com/CarlosMartinsIFPR2020/imagens/blob/c77335105d4679cc52f23fbc1f50d9af40efeb08/pycharm_tela_inicial.png)  


### **Git versão 2.34.1**  

Git é um software para rastrear alterações em qualquer conjunto de arquivos, geralmente usado para coordenar o trabalho entre programadores
que desenvolvem código-fonte colaborativamente durante o desenvolvimento de software. Seus objetivos incluem velocidade, integridade de dados
e suporte para fluxos de trabalho distribuídos e não lineares (milhares de ramificações paralelas em execução em diferentes sistemas).  

_**Instalação:**_

1. Baixar o software pelo site oficial [git.com](https://git-scm.com/downloads), escolhendo a versão de acorso com seu sistema operacional.  
![git_versao](https://github.com/CarlosMartinsIFPR2020/imagens/blob/c655217bcc51183425bdbb17417efecb03a2b9d0/1-git_versao_download.png)  
2. Executar o instalador.  
![git_instalador](https://github.com/CarlosMartinsIFPR2020/imagens/blob/c655217bcc51183425bdbb17417efecb03a2b9d0/2-git_instalador.png)  
3. Clicar em Next.  
![git_instalador](https://github.com/CarlosMartinsIFPR2020/imagens/blob/c655217bcc51183425bdbb17417efecb03a2b9d0/3-git_instalador.png)  
4. Nesta tela deve-se escolher o editor que será usado, no meu caso o Visual Studio Code.  
![git_editor](https://github.com/CarlosMartinsIFPR2020/imagens/blob/c655217bcc51183425bdbb17417efecb03a2b9d0/4-git_instalador_selecionar_editor.png)  
5. Clicar em Next até que a instalação seja finalizada.  
![git_editor](https://github.com/CarlosMartinsIFPR2020/imagens/blob/3c2360e6f2ce7107b8ae9fdb359b51b2d6b2fb2e/git_finalizado.png)  

### **SQLite versão 3.37.2**  

SQLite é uma biblioteca que permite a disponibilização de um pequeno banco de dados na própria aplicação, sem a necessidade de acesso a um SGDB separado,  
Desenvolvido em linguagem C e de código aberto, é indicado para aplicações de pequeno porte, que utilizam poucos dados.  
A grande vantagem dos bancos de dados embutidos está em sua simplicidade, é mais prático implementar e administrar do que a implementação de SGDB´s separados.
Por outro lado, a performance e limitação de recursos são desvantagens do SQLite e soluções semelhantes.

_**Instalação:**_

1. Fazer o download pelo site oficial [SQLite.org](https://www.sqlite.org/download.html)
Escolher a opção de acordo com a versão do sistema operacional.
![SQLite_version](https://github.com/CarlosMartinsIFPR2020/imagens/blob/12113f8d2ad1a42929d078ff6cf5561fd9c50e2a/1-SQLite_version.png)  
2. Tranferir os arquivos baixados para pasta C.  
![SQLite_pasta_c](https://github.com/CarlosMartinsIFPR2020/imagens/blob/12113f8d2ad1a42929d078ff6cf5561fd9c50e2a/2-SQLite_transferir_pasta_C.png)  
3. Conceder permissão de administrador.  
![SQLite_permissao](https://github.com/CarlosMartinsIFPR2020/imagens/blob/12113f8d2ad1a42929d078ff6cf5561fd9c50e2a/3-SQLite_transferir_pasta_C_administrador.png)  
4. Transferir o conteúdo da pasta sqlite-dll para a pasta SQLite.  
![SQLite_conteudo](https://github.com/CarlosMartinsIFPR2020/imagens/blob/12113f8d2ad1a42929d078ff6cf5561fd9c50e2a/5-SQLite_conte%C3%BAdo.png)  

_**Os passos a seguir são para configurar as variáveis de ambiente do windows**_

1. Em "Este Computador", clique direito e acessar Propriedades
![variaveis_windows](https://github.com/CarlosMartinsIFPR2020/imagens/blob/12113f8d2ad1a42929d078ff6cf5561fd9c50e2a/6-SQLite_propriedades_de_ambiente.png)  
2. Configurações avançadas do sistema
![variaveis_windows](https://github.com/CarlosMartinsIFPR2020/imagens/blob/12113f8d2ad1a42929d078ff6cf5561fd9c50e2a/7-SQLite_propriedades_de_ambiente_configura%C3%A7%C3%B5es.png)  
3. Variáveis de ambiente
![variaveis_windows](https://github.com/CarlosMartinsIFPR2020/imagens/blob/12113f8d2ad1a42929d078ff6cf5561fd9c50e2a/8-SQLite_variaveis_de_ambiente.png)  
4. Selecione path e clique em editar
![variaveis_windows](https://github.com/CarlosMartinsIFPR2020/imagens/blob/1004179ae49e1c871a5d3181470feb3d4ebe1f58/9-SQLite_variaveis_de_ambiente_editar_path.png)  
5. Clique em novo
![variaveis_windows](https://github.com/CarlosMartinsIFPR2020/imagens/blob/12113f8d2ad1a42929d078ff6cf5561fd9c50e2a/10-SQLite_variaveis_de_ambiente_editar_novo.png)  
6. Em novo preencha com o endereço do diretorio onde se encontram os arquivos SQLite
![variaveis_windows](https://github.com/CarlosMartinsIFPR2020/imagens/blob/1004179ae49e1c871a5d3181470feb3d4ebe1f58/11-SQLite_caminho_pasta_SQLite.png) 

_**Após esse processo clique OK até sair das configurações**_

7. No CMD digite um comando com a versão do SQLite instalada para certificar-se de que o SQLite está corretamente instalado
![variaveis_windows](https://github.com/CarlosMartinsIFPR2020/imagens/blob/1004179ae49e1c871a5d3181470feb3d4ebe1f58/12-SQLite_teste_CMD.png) 
Será mostrado a versão do SQLite seguido de algumas opções de comandos  

### **SQLiteBrowser versão 3.12.2**  

DB Browser para SQLite é uma ferramenta de código livre usada para criar, editar e projetar bancos de dados SQLite.  

_**Instalação:**_

1. Fazer o download no site oficial
![sqlite_browser](https://github.com/CarlosMartinsIFPR2020/imagens/blob/6fb43739ba4794e43c52e14723661f8b020c7150/1-sqlite_brownser_download.png) 
2. Executar o instalador
![sqlite_browser](https://github.com/CarlosMartinsIFPR2020/imagens/blob/6fb43739ba4794e43c52e14723661f8b020c7150/2-sqlite_brownser_instalador.png) 
3. Aceitar os termos de licensa
![sqlite_browser](https://github.com/CarlosMartinsIFPR2020/imagens/blob/6fb43739ba4794e43c52e14723661f8b020c7150/3-sqlite_brownser_instalador.png) 
4. Adicionar ícone ao desktop
![sqlite_browser](https://github.com/CarlosMartinsIFPR2020/imagens/blob/6fb43739ba4794e43c52e14723661f8b020c7150/4-sqlite_brownser_instalador.png) 
5. Clicar em next
![sqlite_browser](https://github.com/CarlosMartinsIFPR2020/imagens/blob/6fb43739ba4794e43c52e14723661f8b020c7150/5-sqlite_brownser_instalador.png) 
6. Clicar em instalar
![sqlite_browser](https://github.com/CarlosMartinsIFPR2020/imagens/blob/6fb43739ba4794e43c52e14723661f8b020c7150/6-sqlite_brownser_instalador.png) 
7. Após a instalação, pode-se executar o SQLiteBrowser para teste
![sqlite_browser](https://github.com/CarlosMartinsIFPR2020/imagens/blob/6fb43739ba4794e43c52e14723661f8b020c7150/8-sqlite_brownser_instalador.png) 
























