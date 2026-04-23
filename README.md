# ⚙️ Infraestrutura de Hardware: Práticas em Assembly RISC-V

Olá! 👋 Bem-vindo(a) ao repositório de soluções práticas da disciplina de **Infraestrutura de Hardware**. 

Este espaço é dedicado a documentar a resolução de listas de exercícios focadas no entendimento de arquitetura de computadores a baixo nível. Todos os códigos aqui presentes foram desenvolvidos em **Assembly** para a arquitetura **RISC-V** e validados através do simulador **CompSim**.

---

## 🛠️ Tecnologias e Ferramentas

* **Linguagem:** Assembly (RISC-V)
* **Simulador:** CompSim (utilizado para simular a execução das instruções, ciclos de clock e interação com periféricos de entrada/saída).

---

## 📂 Visão Geral das Questões Resolvidas

Os scripts exploram desde lógicas condicionais básicas até a interação direta com periféricos mapeados em memória (Memory-Mapped I/O). Abaixo está o resumo do que cada questão aborda:

* **Questões 1 e 3 - Lógica Condicional e Desempenho:** Implementação de estruturas de decisão (`blt`, `beq`) e conversão de caracteres ASCII para inteiros. Inclui também análises de ciclos de execução, comparando o tempo de execução entre modelos *Dual Cycle* e *Cycle Accurate*.
* **Questão 2 - Manipulação de Caracteres e ASCII:** Algoritmo que processa entradas do teclado em ASCII (reconhecendo espaços e letras) para calcular um sistema de pontuação baseado nas letras digitadas.
* **Questão 4 - Algoritmo de Divisão via Hardware:** Implementação de uma operação de divisão "na raça", utilizando deslocamento de bits (`sll`, `srl`) e subtrações sucessivas para calcular o quociente e o resto.
* **Questão 5 - Interação com Sensores e LEDs:** Leitura de dados de um sensor de temperatura (via pino analógico simulado) e controle de diferentes LEDs (vermelho, amarelo, verde) dependendo das faixas de temperatura atingidas.
* **Questão 6 - Conversão Binária e Display de 7 Segmentos:** Leitura de quatro dígitos binários em ASCII, conversão para o valor decimal correspondente com base em seus pesos e lógica de mascaramento (`andi`) para exibição em um display de 7 segmentos.

---

## 🚀 Como Executar os Códigos

Para rodar qualquer um dos scripts deste repositório:

1. Faça o download ou clone este repositório.
2. Abra o aplicativo **CompSim**.
   Download: [CompSim](http://compsim.crato.ifce.edu.br/download.html)
   
4. Carregue o arquivo do código-fonte no ambiente de edição do simulador.
5. Utilize a interface de periféricos do CompSim (como o *Simple Keyboard* e *Simple Video*) caso a questão exija entrada e saída de dados.
6. Execute o código em modo de ciclo (Passo a Passo) ou execução contínua para observar o estado dos registradores e da memória.

---
*Repositório criado para fins acadêmicos e consulta de estudos de arquitetura RISC-V.*
