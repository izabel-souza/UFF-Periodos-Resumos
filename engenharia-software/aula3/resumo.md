# Casos de Uso

Tecnica pra capturar requisitos funcionais, descreve o sistema pela visao do usuario. (foca no cenario tipico, mas os cenarios alternativos tambem sao descritos, conhecido como extensoes, indicando o ponto em que estende o cenario tipico e o ponto em que retorna ao cenarios tipico).


Tem Atores

Exemplos: Usuarios, cliente, caixa do supermercado, gerente, etc.


Tipos de atores
* primario sao beneficiados diretamente pelo caso de uso
* secundarios sao atores que participam como coadjuvantes no caso de uso


Estrutura simples de um caso de uso
1. Nome
2. Cenario tipico
3. Cenario alternativos


#### Perguntas para identificar atores e casos de uso

* Quem utiliza o sistema?
* Como é o uso do sistema?
* Quais informacoes sao fornecidas ou obtidas do sistema?
* Como o sistema e mantido?
* Quais outros sistemas interagem com esse sistema?
* Quando tudo da certo, como o sistema se comporta?
* Algo pode ocorrer de forma diferente nesse passo?
* O que pode dar errado nesse passo?



#### Diagrama de casos de uso - relacionamento de extensao

* Encapsula um cenario alternativo complexo em um outro caso de uso
* É condicional: utiliza o campo "gatilho" para definir o momento que entra em ação.
* Pode ser visto como um remendo do caso de uso base


#### Diagrama de casos de uso - relacionamento de inclusao

* adicao de um comportamento especifico em um ponto determinado do caso de uso
* é bem util quando esse comportamento é repetido em diversos casos de uso do sistema
