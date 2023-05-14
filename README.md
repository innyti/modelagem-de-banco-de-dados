<h1>SGBD</h1>

```
•	É o que gerencia o banco de dados;
•	Interface para incluir, alterar ou consulta;
•	Tudo que fazemos passa por ele;
•	É comum que confundam o SGBD com o banco de dados.
```

Os mais utilizados: MySQL, OROCLE, SQLSERVER, entre outros.  <br/> 
Está ligado ao  “Baixo Nível” – linguagem das máquinas – modelos fisicos. <br/> 
“Alto Nível” – está relacionado a linguagem das pessoas – modelos conceituais. <br/> 

<h2>Mini-Mundo</h2>
É um recorte do mundo real. <br/> 

![alt text](https://github.com/innyti/modelagem-de-banco-de-dados/blob/66483757e257ceca2019bea99e5f986601e97347/Images/Sem%20t%C3%ADtulo.png)

<h3> Abstração</h3>
É um processo mental que permite escolher ou isolar um aspecto de coisas complexas, tem como finalidade simplificar. <br/> 

```
•	É subjetivo;
•	Ignora-se os detalhes;
```

<h4>Entrevista</h4>
A modelagem de dados é a base para se ter um bom projeto final do banco de dados. Uma das etapas mais importantes deste processo é a entrevista com os(as) clientes, na qual serão identificadas as regras de negócio do projeto. Quando não identificamos as necessidades do projeto, pode surgir novamente a necessidade de realizar esta etapa, gerando assim, atraso em todo o processo. <br/> 
A entrevista dará todo o direcionamento ao nosso projeto. Através dela, conhecemos todos os detalhes do negócio e podemos estruturar os próximos passos. Um fator importante desse processo é saber de quem vamos colher as informações, ou seja, devemos entrevistar uma ou mais pessoas que possam passar todos os detalhes importantes do negócio. <br/> 
Outro fator é escolher as perguntas ideais para definir todos os pontos-chaves do projeto. Nessa etapa, a pessoa que faz a entrevista precisa ter um conhecimento prévio sobre os pontos mais relevantes para a construção do projeto, o que possibilita coletar informações realmente essenciais para a modelagem do banco de dados. <br/> 
Em resumo, a entrevista é a base para construir um projeto coerente e que atende às necessidades do(a) cliente. <br/> 

<h5>MER</h5> 
Modelo Entidade de Relacionamento
```
•	Modelo conceitual;
•	Usado para descrever objetos, suas característica e como se relacionam
```
<h6>DER</h6>
Diagrama Entidade de Relacionamento
```
•	É a reapresentação gráfica do MER;
•	Muitas vezes é usado como sinônimo; 
•	O diagrama facilita a comunicação entre todos; 
```
--
<h7>Entidade </h7>
```
•	Entidade é um objeto único no mundo real;
1.	Clientes de uma empresa
2.	Carros que são vendidos
3.	Departamentos de vendas
•	Pode ser abstrata ou concreta;
```

ENTIDADES<br/> 
Entidade Forte<br/> 
```
Existe independentemente de outra entidade
```
Uma entidade forte sempre tem a chave primária no conjunto de atributos que descreve a entidade forte. A entidade forte, por si só, possui um atributo que poderá ser utilizado como chave primária.</B>

Entidade Fraca<br/> 
```
Depende da existência de outra entidade 
```
A entidade fraca não possui a chave primária, mas tem uma chave parcial que discrimina de maneira única as entidades fracas. A entidade fraca possui uma chave composta formada a partir da chave primária da entidade forte e chave parcial da entidade fraca</B>