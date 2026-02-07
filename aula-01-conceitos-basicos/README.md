# Aula 01 – Conceitos Básicos sobre Banco de Dados 

📅 Data da aula: 30/02/2026

Esta aula abordou a organização dos dados, o funcionamento de sistemas,
a estrutura de desenvolvimento de software e os tipos de bancos de dados
utilizados no mercado.

## 📌 O que é um Banco de Dados
Um Banco de Dados é um conjunto de dados organizados dentro de uma ou mais tabelas,
que podem ou não possuir relacionamento entre si.

Seu objetivo é garantir **organização, padronização e estrutura** para as informações
utilizadas em um sistema.

### Exemplos:
- **Dado**: Aluno  
- **Tabela**: Múltiplos alunos  
- **Banco de Dados**: Conjunto de dados relacionados, como alunos, matrículas,
horários, turmas e professores.


## 📊 Dados, Informação e Conhecimento
Diferença entre os conceitos apresentados em aula:

- **Dado**: menor parte de algo que precisa ser armazenado
- **Informação**: resultado da junção e interpretação dos dados
- **Conhecimento**: obtido a partir da análise das informações

### Exemplo:
- `25` → dado  
- `falta` → dado  
- `25 faltas` → informação  
- Análise das faltas → conhecimento  

## 🌐 Banco de Dados dentro de um Sistema
Durante a aula foi apresentado que o front-end não acessa o banco de dados diretamente.
A comunicação ocorre por meio do servidor de aplicação, que processa as requisições,
consulta o banco de dados e retorna a resposta ao front-end.

```
Front-end → Servidor de Aplicação → Banco de Dados
Front-end ← Servidor de Aplicação (requisição HTTP contendo JSON) ← Banco de Dados
```

## 🔁 Ordem Base de Desenvolvimento
Durante a aula foi apresentada a sequência base para o desenvolvimento de sistemas,
reforçando a importância do planejamento antes da implementação.

### Sequência de desenvolvimento
1. Levantamento de Requisitos  
2. Banco de Dados  
3. Back-end  
4. Front-end


## 🧠 Estrutura da Disciplina
Distribuição do conteúdo da matéria:

- **Modelagem de Banco de Dados** → 40%  
- **Script SQL** → 60%


## 📐 Modelagem de Dados
A modelagem de dados é a etapa responsável por **organizar a estrutura do software**
antes da implementação.

Ela define como os dados serão organizados, armazenados e relacionados.

A disciplina abordará:
- **Modelagem Conceitual**
- **Modelagem Lógica**

## 🗄️ Tipos de Banco de Dados

### Banco de Dados Relacional (SQL)
Exemplos citados:
- MySQL (foco da disciplina)
- MariaDB
- PostgreSQL
- SQL Server

Características:
- Dados **estruturados**
- **Relacionamentos** entre dados
- **Consistência e integridade**
- Uso de **transações (ACID)**

**Exemplos de uso**: bancos, ERPs, sistemas financeiros.


### Banco de Dados Não Relacional (NoSQL)
Exemplos citados:
- MongoDB
- Cassandra

Características:
- Grande **volume de dados**
- **Alta escalabilidade e performance**
- Dados **flexíveis ou não estruturados**
- Estrutura muda com frequência

**Exemplos de uso**: redes sociais, Big Data, logs e cache.

## 🧩 Planejamento de Software a Longo Prazo
Foi discutida a importância de planejar sistemas com uma **vida útil mínima de 10 anos**.

O planejamento inicial pode gerar maior custo no início do projeto,
mas permite crescimento, estabilidade e atualizações futuras.

## 🎓 Mercado e Certificações   
Foi citada a existência de **certificações Oracle** voltadas para Banco de Dados,
especialmente para a área de **DBA (Administrador de Banco de Dados)**.
