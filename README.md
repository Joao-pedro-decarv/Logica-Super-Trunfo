# 🃏 Desafio Super Trunfo - Países  

Bem-vindo ao desafio **Super Trunfo - Países**!  
Este projeto tem como objetivo a criação de um sistema para comparar cartas de cidades, explorando diferentes atributos como população, área, PIB e densidade populacional.  

O desafio é dividido em três níveis de dificuldade (**Novato**, **Aventureiro** e **Mestre**), cada um adicionando novas funcionalidades e aumentando a complexidade para promover um aprendizado progressivo.  

---

## 🥉 Nível Novato  

### Funcionalidades:
- Cadastro de cartas com os seguintes atributos:
  - Estado  
  - Código da carta  
  - Nome da cidade  
  - População  
  - Área  
  - PIB  
  - Número de pontos turísticos  
- Comparação simples entre dois atributos escolhidos.  
- Determinação da carta vencedora:
  - **Maior valor vence** (ex.: população, área, PIB).  
  - **Menor valor vence** apenas na **densidade populacional**.  

### Entrada de Dados:
- Inserção manual via terminal.  

### Saída de Dados:
- Exibição organizada das informações da carta.  
- Exibição do vencedor da rodada.  

---

## 🥈 Nível Aventureiro  

### Novidades em relação ao Novato:
- **Menu interativo** (via `switch`) para o usuário escolher qual atributo comparar.  
- **Comparação aninhada** para lidar com múltiplos atributos.  

### Funcionalidades:
- Comparação de atributos escolhidos via menu.  
- Exibição clara da carta vencedora e do atributo utilizado na comparação.  

---

## 🥇 Nível Mestre  

### Novidades em relação ao Aventureiro:
- Escolha de **dois atributos** para comparação entre cartas.  
- **Lógica de decisão avançada** utilizando operadores ternários e condicionais encadeados.  
- **Menus dinâmicos** para navegação fluida.  
- Tratamento de **empates**, exibindo mensagens apropriadas.  

### Funcionalidades:
- Comparação simultânea de dois atributos.  
- Exibição interativa dos resultados.  
- Sistema mais robusto para lidar com diferentes cenários.  

---

## 📋 Requisitos Funcionais (Comuns a todos os níveis)
- O sistema deve permitir o **cadastro de cartas**.  
- Deve ser possível **comparar cartas** com base nos atributos definidos.  
- O resultado da comparação deve ser exibido de forma clara, indicando a carta vencedora.  

---

## 📌 Requisitos Não Funcionais
- **Usabilidade:** Interface simples e intuitiva.  
- **Performance:** Execução sem atrasos perceptíveis.  
- **Manutenibilidade:** Código bem estruturado e documentado.  
- **Confiabilidade:** Sistema robusto, capaz de lidar com entradas inválidas.  

---

## 🚀 Tecnologias Utilizadas
- **Linguagem:** C  
- **Conceitos aplicados:**  
  - Estruturas condicionais (`if`, `if-else`, `switch`)  
  - Estruturas aninhadas  
  - Operadores ternários  
  - Lógica de comparação  

---

## 📂 Estrutura do Projeto
```bash
├── nivel_novato/        # Implementação básica
├── nivel_aventureiro/   # Menu interativo e comparação aninhada
├── nivel_mestre/        # Lógica avançada e menus dinâmicos
└── README.md            # Documentação do projeto
