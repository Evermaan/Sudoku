# ⚙️ SUDOKU
 
## 📜 Descrição
Este repositório contém o conteúdo  de um jogo desenvolvido chamado SUDOKU no 5º/6º Semestre de Ciência da Computação da UDF.  
Nossa linguagem utilizada foi Python.

## 👥 Participantes
- 👩‍🏫 Profesora Kadidja Valéria
- 👤 Everman | RGM: 30333717
- 👤 Ícaro | RGM: 31335519
- 👤 Daniel Medeiros | RGM: 29381169


## 📘 SUDOKU
- 📖 **Definição**: é um jogo de lógica e raciocínio matemático, cujo objetivo principal é preencher uma grade com números obedecneto uma série de regras.
- 📖 **Tema**: organização e desafio intelectual
- 📖 **Desenvolvimento**:
   -  **Planejamento**: optamos por implementar o formato clássico do Sudoku (9x9), devido à sua popularidade e estrutura desafiadora. As responsabilidades foram atribuídas entre os membros da equipe, e as tarefas foram divididas.
   -  **Configuração do ambiente**: configuramos o ambiente no Thonny, estruturamos o projeto em arquivos organizados e criamos um design básico, com representação inicial do tabuleiro e planejamento da interface.
   -  **Lógica**: criar os tabuleiros, garantir que as regras sejam respeitadas, inserir os números e fazer a lógica funcionar.
   -  **Interface**: Desenvolvemos a lógica para criar tabuleiros válidos, garantindo que as regras do Sudoku fossem respeitadas. Implementamos a funcionalidade de inserir números no tabuleiro e validamos todas as jogadas para assegurar o funcionamento correto do jogo.
   -  **Testes**: Realizamos testes jogando várias partidas para identificar possíveis bugs e garantir o funcionamento correto de todos os recursos implementados.
- 📖 **Tecnologias utilizadas**:
   -  Linguagem de programação Python.
   -  IDE(Integrated Development Environment) Thonny.
   -  Biblioteca Pygame, para desenvolvimento de jogos e aplicações multimídia.
   -  Biblioteca Random, usada para gerar números aleatórios e trabalhar com escolhas aleatórias.
   -  Biblioteca Math, que fornece funções matemáticas avançadas.
- 📖 **Complexidade do jogo**:
   -  A maioria das funções tem complexidade constante (O(1)), devido ao tamanho fixo do tabuleiro e natureza das operações, no entanto, algumas funções que percorrem o tabuleiro ou manipulam quadrantes podem ter complexidade O(n^2).
   -  A gestão da complexidade foi feita de maneira estratégica para garantir eficiência, principalmente considerando que o tamanho é fixo e relativamente pequeno.
- 📖 **Regras e jogabilidade**:
   -  É um quebra-cabeça de lógica baseado em números que é jogado em um tabuleiro 9x9.
   -  O tabuleiro é composto por 9 linhas e 9 colunas, resultando em 81 células.
   -  O tabuleiro é subdivido em 9 quadrantes de 3x3 células, totalizando 27 quadrantes.
   -  O objetivo é preencher as células vazias com números de 1 a 9.
   -  Cada número de 1 a 9 deve aparecer uma única vez em cada linha, uma única vez em cada coluna e uma única vez em cada quadrante 3x3.
   -  Nenhum número pode se repetir na mesma linha, coluna ou quadrante.
   -  O jogo começa com algumas células já preenchidas. Estas células fornecem pistas para o jogador.
   -  O número de células preenchidas pode variar, dependendo da dificuldade do jogo (quanto mais números iniciais, mais fácil o jogo).
   -  O jogador deve preencher as células restantes, sem violar as regras de que cada número aparece uma vez por linha, coluna e quadrante.
   -  A resolução é feita por tentativa e erro, lógica dedutiva e, em alguns casos, algoritmos complexos, mas em um jogo básico, o processo é puramente lógico.
   -  O objetivo final é preencher todas as células do tabuleiro de forma que as regras sejam respeitadas.
- 🎬 **Link para vídeo do jogo**:
   -  https://www.youtube.com/watch?v=xJhuOtLokvg


