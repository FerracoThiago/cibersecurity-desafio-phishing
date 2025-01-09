# Phishing para captura de senhas do Facebook

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

Etapa 1: Acesso root: ``` sudo su ```
Etapa 2: Iniciando o setoolkit: ``` setoolkit ```
Etapa 3: Tipo de ataque: ``` Social-Engineering Attacks ```
Etapa 4: Vetor de ataque: ``` Web Site Attack Vectors ```
Etapa 5: Método de ataque: ```Credential Harvester Attack Method ```
Etapa 6: Método de ataque: ``` Site Cloner ```
Etapa 7: Obtendo o endereço da máquina: ``` ifconfig ```
Etapa 8: Inserir URL para clone: http://www.facebook.com

### Resutados Sem a proteção do Facebook

![Alt text](./passwd.png "Optional title")

É importante saber que sites bastantes conhecidos atualmente contém diversas proteções rígidas contra qualquer script que seja malicioso, para isso temos que dar uma volta por cima deles...
### Contornando a proteção do Facebook

Quando a clonagem de site não é bem-sucessida , podemos utilizar outra maneira através do ``` Custom Import ``` oferecida na 6ª etapa do nosso ataque.


Essa opção nos permite, no lugar de uma URL, utilizar um arquivo ``` html ``` da nossa própria máquina para utilização do ataque.
Portanto, é necessário efetuar alguns "malabarismos" para um phishing limpo e eficiente.

