# 🧠 Guia de Sobrevivência: Domínio de Terminal (CLI)

Este repositório foi criado como parte da disciplina de **Sistemas Operacionais**, utilizando o simulator [Terminal Master](https://andersonrmgomes.github.io/terminal-master/) para praticar comandos essenciais de Windows e Linux.



## 🚀Introdução
A interface de Linha de comando (CLI) é uma ferramenta poderosa que permite interagir com o núcleo do sistema operacional. Dominar esses comandos é fundamental para automação de tarefas, administração de servidores e desenvolvimento de software.



## 🤖Comandos Aprendidos

Abaixo, aprenseto uma lista dos principais comandos praticados durante o treinamento gamificado:

|Comando |Função |Sistema|Exemplo de Uso|
|:--- |:--- |:--- | :--- |
|`pwd`| `Exibe o diretório atual (caminho)`| `Ambos` | `pwd`|
|`cd`|`Altera o diretório de trabalho`|` Ambos`|`cd /home/usuario`| 
|`mkdir`|`Cria um novo diretório`|`Ambos`|`mkdir projetos`|
|`rmdir`|`Remove um diretório vazio`|`Ambos`|`rmdir projetos`|
|`echo`|`Exibe texto ou escreve em arquivo`|`Ambos`|`echo "Olá Mundo`|
|`dir`|`Lista arquivos e pastas do diretório`|`Windows`|`dir`|
|`del`|`Remove arquivo`|`Windows`|`del arquivo.txt`|
|`cp`|`Copia arquivos`|`Windws`|`copy arquivo.txt D:\Backup\`|
|`move`|`Move ou renomeia arquivos/pastas`|`Windows`|`move arquivo.txt D:\NovaPasta\`|
|`type`|`Exibe conteúdo de arquivos`|`Windows`|`type arquivo.txt`|
|`icacls`|`Gerencia permissões de arquivos/pastas`|`Windows`|`icacls arquivo.txt /grant Usuario:F`|
|`tasklist`|`Lista processos em execução`|`Windows`|`tasklist`|
|`findstr`|`Busca texto dentro de arquivos`|`Windows`|`findstr "erro" log.txt`|
|`notepad`|`Cria/edita arquivo`|`Windows`|`notepad novo.txt`|
|`dir /s`|`Lista arquivos recursivamente em subpastas`|`Windows`|`dir /s *.txt`|
|`dir /a`|`Lista todos os arquivos, incluindo ocultos e de sistema`|`Windows`|`dir /a`|
|`ls`|`Lista arquivos e pastas do diretório`|`Linux`|`ls -l`|
|`rm -r`|`Remove diretório com conteúdo`|`Linux`|`rm -r pasta`|
|`mv`|`Move ou renomeia arquivos/pastas`|`Linux`|`mv arquivo.txt nova_pasta/ `|
|`cat`|`Exibe conteúdo de arquivos`|`Linux`|`cat arquivo.txt`|
|`touch`|`Cria arquivo vazio`|`Linux`|`touch novo.txt`|
|`ls -la`| `Lista todos os arquivos, incluindo ocultos (-a) e mostra detalhes completos como permissões, dono, tamanho e data (-l)`| `Linux`|`ls -la /home/usuario`|
|`find`|`Procura arquivos e diretórios de forma recursiva, baseado em nome, tipo, tamanho ou outros critérios`|`Linux `|`find /home/usuario -name "*.txt"`|
|`grep`|`Procura por texto dentro de arquivos, muito usado para filtrar resultados`|`Linux`|`grep "erro" log.txt`|
|`chmod`|`Modifica permissões de arquivos e diretórios`|`Linux`|`chmod 755 script.sh`|
|`ps aux`|`Lista todos os processos em execução com detalhes`|`Linux`|`ps aux`|