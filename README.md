# 📊 Projeto Temático 1 - ScoreGame

Este documento fornece um resumo detalhado da documentação do **Projeto Temático 1**, conforme apresentado no arquivo [1-projeto.pdf](https://github.com/Eduardo-Bauer/projeto_tematico_1/blob/main/projeto_tematico_1/1_documentacao/1-projeto.pdf). O projeto foi desenvolvido como parte das atividades do curso de **Ciência da Computação** da **Universidade de Caxias do Sul (UCS)**.

## 📘 Sumário

- [1. Introdução](#1-introdução)
- [2. Objetivos](#2-objetivos)
- [3. Requisitos do Sistema](#3-requisitos-do-sistema)
- [4. Modelagem do Sistema](#4-modelagem-do-sistema)
- [5. Implementação](#5-implementação)
- [6. Considerações Finais](#6-considerações-finais)

---

## 1.📚 Introdução

O ScoreGame é uma aplicação em python sem usar programação orientada a
objetos, visando fornecer a análise e visualização das estatísticas de três
modalidades esportivas, sendo elas, futebol feminino, basquete e boxe +92kg
Masculino nas últimas 4 olimpíadas dos respectivos ganhadores das medalhas,
ouro, prata e bronze.

Futebol feminino, terá as estatísticas levantadas: Registro de gols, chutes ao
gol, assistências, defesas por time, faltas, cartões amarelos, cartões vermelhos.
Basquete, terá as estatísticas levantadas: Total de pontos, assistências,
porcentagem de arremessos de 2 e 3 pontos, rebotes no geral, bloqueios, faltas
cometidas e sofridas e lances livres convertidos e errados.

Boxe +92kg, terá as estatísticas levantadas: Total de pontos durante a partida
e seus pontos por rodada, nota dos 5 juízes nas rodadas e rodadas vencidas.

## 2.🎯 Objetivos

### Objetivo Geral

Desenvolver um sistema eficiente para gerenciamento de dados que atenda às necessidades específicas identificadas durante a análise de requisitos.

### Objetivos Específicos

- Estabelecer uma conexão robusta entre o aplicativo Python e o banco de dados MySQL.
- Implementar operações de CRUD (Create, Read, Update, Delete) de forma eficaz.
- Garantir a integridade e segurança dos dados manipulados pelo sistema.
- Proporcionar uma interface de usuário intuitiva e de fácil utilização.

## 3.🔧 Requisitos do Sistema

### Requisitos Funcionais

- O sistema deve permitir a inserção, consulta, atualização e exclusão de registros no banco de dados.
- Deve ser possível realizar buscas específicas com base em critérios definidos pelo usuário.
- O sistema deve fornecer feedback claro e imediato após cada operação realizada.

### Requisitos Não Funcionais

- O sistema deve ser desenvolvido utilizando a linguagem Python.
- O banco de dados utilizado deve ser o MySQL.
- A aplicação deve ser executável em ambientes Windows e Linux.
- O código-fonte deve ser modularizado para facilitar manutenção e futuras expansões.

## 4.🧩 Modelagem do Sistema

A modelagem do sistema inclui diagramas que representam a estrutura e o fluxo de dados:

- **Diagrama de Entidade-Relacionamento (DER)**: Representa as entidades envolvidas no sistema e seus relacionamentos.
- **Diagrama de Casos de Uso**: Ilustra as interações entre os usuários e o sistema, destacando as funcionalidades disponíveis.

## 5.💻 Implementação

A implementação do sistema segue as melhores práticas de desenvolvimento de software:

- **Estrutura Modular**: O código é organizado em módulos separados por funcionalidades, como conexão com o banco de dados, operações de CRUD e interface de usuário.
- **Tratamento de Exceções**: O sistema inclui mecanismos para lidar com erros e exceções, garantindo maior robustez.
- **Validação de Dados**: Antes de qualquer operação no banco de dados, os dados são validados para assegurar sua consistência.

## 6.📝 Considerações Finais

O desenvolvimento deste projeto proporcionou uma experiência prática valiosa, permitindo a aplicação dos conhecimentos adquiridos ao longo do curso. A documentação completa, disponível no arquivo [1-projeto.pdf](https://github.com/Eduardo-Bauer/projeto_tematico_1/blob/main/projeto_tematico_1/1_documentacao/1-projeto.pdf), oferece uma visão detalhada de cada etapa do projeto, servindo como referência para futuros desenvolvimentos.

---

*Para mais detalhes e informações específicas, consulte o documento completo em [1-projeto.pdf](https://github.com/Eduardo-Bauer/projeto_tematico_1/blob/main/projeto_tematico_1/1_documentacao/1-projeto.pdf).*


## ⚙️ Configuração do Banco de Dados

Certifique-se de que o MySQL esteja instalado e em execução em sua máquina. As configurações padrão esperadas são:

- **Host**: `localhost`
- **Usuário**: `root`
- **Senha**: (vazia)

Caso seja necessário remover a senha do usuário `root`, execute o seguinte comando no prompt do MySQL:

```sql
SET PASSWORD FOR 'root'@'localhost' = '';
```

## ▶️ Executando o Projeto

1. Clone o repositório:

   ```bash
   git clone https://github.com/Eduardo-Bauer/projeto_tematico_1.git
   ```

2. Instale as dependências:

   ```bash
   pip install mysql-connector-python
   ```

3. Execute o aplicativo:

   ```bash
   python tela_login.py
   ```

## 📌 Observações

- Este projeto foi desenvolvido com fins educacionais, visando a aplicação prática dos conceitos aprendidos em sala de aula.
- Contribuições e sugestões são bem-vindas para aprimorar o sistema.
