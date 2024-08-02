Aqui está o README ajustado conforme solicitado:

---

# 🎓 Simulador de ENEM

Um simulador do Exame Nacional do Ensino Médio (ENEM) integrado a um banco de questões e usuários, desenvolvido utilizando CSharp, WindowsForms e SQLServer pelo Visual Studio 2019 (hoje, ele está sendo executado no 2022).

<div align="center">
  <img width="500" src="./Resources/featured-image.jpg">
</div>

## 📚 Tabela de Conteúdos

- [🎓 Simulador de ENEM](#-simulador-de-enem)
  - [📚 Tabela de Conteúdos](#-tabela-de-conteúdos)
  - [📋 Descrição](#-descrição)
    - [🚀 Funcionalidades](#-funcionalidades)
      - [👤 Usuário Padrão](#-usuário-padrão)
      - [🔑 Administrador](#-administrador)
    - [🌐 Acesso](#-acesso)
  - [⚙️ Construção](#️-construção)
    - [💻 Tecnologias](#-tecnologias)
    - [🛠️ Ferramentas](#️-ferramentas)
    - [📌 Versão](#-versão)
  - [✏️ Aprendizado](#️-aprendizado)
  - [✒️ Autores](#️-autores)
  - [🎁 Agradecimentos](#-agradecimentos)
  - [📨 Contato](#-contato)

## 📋 Descrição

### 1. Introdução

O projeto foi construído a partir de um trabalho anterior que nos foi imposto, e a partir dele evoluímos de forma que ficasse mais intuitivo ao usuário. Escolhemos este tema tendo em mente o cenário atual em que nós mesmos nos encontramos: último ano do Ensino Médio, época de concursos e do Exame Nacional do Ensino Médio (ENEM) que nos faz sentir pressionados e ansiosos quanto ao nosso futuro. Queremos criar uma ferramenta que auxilie quem estiver, futuramente, na mesma situação que nós ou mesmo estudantes do 3º Ano do Ensino Médio que não farão concurso público, mas que precisam de ajuda em seu ano letivo.

### 1.1 Objetivos

#### Geral

O programa dispõe de dois sistemas de entrada:

- **Entrada como usuário padrão:** O usuário se registra e então realiza o login com sua conta, recebendo acesso às questões implantadas na plataforma. Também há a opção de realizar um simulado, onde a plataforma conta o tempo decorrido durante a resolução, quantas questões foram respondidas e os acertos, armazenando no histórico do aluno.
  
- **Entrada como administrador:** Será possível cadastrar questões de acordo com as matérias: Biologia, Educação Física, Filosofia, Física, Geografia, História, Inglês, Matemática, Português, Química, e a opção para quem se interessa na área de informática, Desenvolvimento de Sistemas. Ao registrar a questão, o usuário deverá registrar o enunciado e 5 respostas (A, B, C, D ou E), indicando qual é a correta, bem como o gabarito comentado da questão.

#### Específicos

1. O formulário de login exige os campos “Usuário” e “Senha” informados, não podendo repetir nomes de usuário. Também haverá a possibilidade de trocar a senha e, enquanto estiver usando a conta, haverá a opção de sair dela e então voltar para o menu.
   
2. O ambiente do programa varia com a matéria da questão que será respondida, fornecendo assim um plano de fundo agradável ao usuário.
   
3. Para uso de “teste” do usuário, haverá a área “responder questões”, em que será possível escolher a matéria que desejar e não haverá contagem delas para o histórico.
   
4. Desenvolvemos o sistema de histórico, em que o programa conta quantas questões o usuário respondeu e quantas acertou. Com base nisso, há o sistema de dificuldade, que diz o nível da questão com base na quantidade de acertos em relação a quantas pessoas erraram ou acertaram.

### 1.2 Contribuições

Nosso foco é no auxílio à comunidade escolar, contribuindo como um método de estudo para alunos, sobretudo, para alunos do terceiro ano do ensino médio, dando a possibilidade para o usuário de responder diversas questões, todas com direito a gabarito comentado. A plataforma também poderá ser usada, por exemplo, por um professor ou até mesmo pela direção de um colégio, que poderá registrar as questões desejadas e então pedir aos alunos para respondê-las como uma plataforma de interação com os alunos.

### 1.3 Justificativa

Acreditamos que um aluno deve ter acesso a um diversificado leque de opções quando se trata de estudo: pela escrita, pelo áudio ou pelo visual, e também através de questões. Optamos por um programa com este tema tendo em mente a ajuda que podemos fornecer à comunidade escolar e principalmente aqueles que buscam resolver questões de concurso frequentemente com a intenção de ingressar numa faculdade.

### 1.4 Delimitações

Como todo projeto, sempre há algo que se pode melhorar. No caso do programa desenvolvido, gostaríamos de ter não só nos limitado a uma plataforma de questões do 3º Ano do Ensino Médio e de Informática, mas também de questões de outros anos letivos (6º, 7º, 8º e 9º ano do Ensino Fundamental e 1º e 2º ano do Ensino Médio), porém não nos foi possível por questão de tempo. Também queríamos ter implementado efeitos sonoros de erros e acertos, além de uma música de fundo para a plataforma, porém também não conseguimos a tempo da entrega do trabalho, além da criptografia de senha, que não conseguimos inserir no programa pelo mesmo motivo. Finalmente, queríamos ter inserido um sistema de títulos ao usuário padrão, em que o mesmo recebesse um apelido caso acertasse muitas questões de uma mesma matéria, por exemplo: user123 acertou 95% das 20 questões de história que resolveu, então receberia o título de historiador, porém não foi possível implantar esse sistema a tempo.

### 🚀 Funcionalidades

As funcionalidades disponíveis para os usuários estão listadas abaixo:

#### 👤 Usuário Padrão

- Registro e login de usuário.
- Acesso a questões implantadas na plataforma.
- Realização de simulados com contagem de tempo, questões respondidas e acertos armazenados no histórico.
- Possibilidade de responder questões de diferentes matérias sem contabilização para o histórico.

#### 🔑 Administrador

- Cadastro de questões por matéria: Biologia, Educação Física, Filosofia, Física, Geografia, História, Inglês, Matemática, Português, Química e Desenvolvimento de Sistemas.
- Registro de enunciados e cinco respostas (A, B, C, D ou E) com indicação da correta e gabarito comentado.

### 🌐 Acesso

🖇️ [Clique aqui para acessar o repositório do projeto no GitHub](#)

## ⚙️ Construção

Resumo geral dos recursos utilizados na construção do projeto.

### 💻 Tecnologias

Tecnologias utilizadas na construção do projeto:

![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white)![SQLServer](https://img.shields.io/badge/sql%20server-%23CC2927.svg?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)

### 🛠️ Ferramentas

Ferramentas utilizadas na construção do projeto:

![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91.svg?style=for-the-badge&logo=visual-studio&logoColor=white)
![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white)

### 📌 Versão

Utilizamos o Git para o controle de versão.

Versão atual: 1.0 (primeira versão)

## ✏️ Aprendizado

Ao fazer esse projeto, aprendemos a:

- Desenvolver um projeto completo utilizando CSharp e WindowsForms.
- Implementar e gerenciar um banco de dados SQLServer.
- Criar interfaces amigáveis e intuitivas para o usuário final.
- Implementar funcionalidades de login e gestão de usuários.
- Gerenciar e armazenar informações de questões e resultados de usuários.
- Utilizar ferramentas de desenvolvimento como Visual Studio para codificação e depuração.
- Aplicar fortemente os conceitos de Programação Orientada a Objetos (POO) com a linguagem C# para a modelagem e construção do sistema.

## ✒️ Autores

* **Milton Salgado Leandro**
* **Jefferson Dutra**
* **Oscar Sysak Neto**

## 🎁 Agradecimentos

* Agradecemos aos professores e colegas pela orientação e apoio durante a realização deste projeto.
* Agradecemos também a você, visitante, por visualizar o nosso projeto!

## 📨 Contato

[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](www.linkedin.com)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&

logo=gmail&logoColor=white)](mailto:seu-email@gmail.com)