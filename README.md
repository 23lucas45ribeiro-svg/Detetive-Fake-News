# 🕵️‍♂️ Detetive de Fake News

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

Este é um projeto acadêmico interdisciplinar, focado na disciplina de Filosofia, desenvolvido para combater o problema atual da desinformação na internet.Tendo em vista a forte influência que as *Fake News* exercem na política e na sociedade, o **Detetive de Fake News** atua como uma ferramenta de checagem inicial para inibir a propagação de inverdades.

O objetivo principal do site é permitir que o usuário insira uma notícia e, através de uma validação em um banco de dados interno, descubra se ela é **Verdadeira** ou **Falsa**.

---

## 🚀 Funcionalidades

- **Validação Dupla**: O sistema permite a verificação tanto pela descrição/título da notícia quanto pela inserção direta da URL[cite: 2].
- **Prevenção de Erros**: Validação de campos vazios utilizando `.trim()` para evitar requisições nulas[cite: 2].
- **Simulação de Processamento**: Implementação de `setTimeout` (atraso de 3 segundos) para simular o tempo de resposta de uma API real e melhorar o feedback ao usuário[cite: 2].
- **Retorno Detalhado**: Ao classificar uma notícia, a aplicação não apenas informa seu status, mas fornece o nome da fonte de checagem (ex: *GOV.BR*, *G1.GLOBO*) e o link oficial para leitura aprofundada[cite: 2].
- **Interface Responsiva**: Design moderno com cartões estilizados (`hover` effects e `box-shadow`) e uma grade fluida para adaptação em dispositivos móveis, além de navegação âncora[cite: 3, 1].

---

## 👥 Equipe de Desenvolvimento

O projeto foi construído colaborativamente, simulando um ambiente de trabalho real:

- **Lucas Ribeiro**: Programador Front-End 
- **Isaac Moreira**: Programador Front-End 
- **Isaias Brito**: Programador Back-End (Lógica JS) 
- **Edson Braga**: Testador (QA) 
- **Diogo Alvino**: Orientador do Projeto 

---

## 🛠️ Detalhes Técnicos

A aplicação é puramente **Client-Side**, dispensando servidores complexos para facilitar o acesso educacional:

- **Lógica de Pesquisa (`index.js`)**: Utiliza os métodos `toLowerCase()` para tornar a busca *case-insensitive* e `includes()` para varrer o array `bancoNoticias`[cite: 2].
- **CSS Grid/Flexbox (`style.css`)**: Aplicação de `grid-template-columns: repeat(auto-fit, minmax(260px,1fr))` para garantir que a seção de desenvolvedores e dicas se ajustem automaticamente à largura da tela do dispositivo[cite: 3].

---

## 🔧 Como Executar o Projeto

1. Clone o repositório para a sua máquina:
   ```bash
   git clone [https://github.com/23lucas45ribeiro-svg/detetive-fake-news.git](https://github.com/23lucas45ribeiro-svg/detetive-fake-news.git)

2.Acesse o diretório do projeto.

3.Abra o arquivo index.html em qualquer navegador web moderno. Não é necessário ambiente virtual ou servidor local.
