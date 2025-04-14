# Pizzaria - Pedido de Pizza

## Descrição Geral

Este aplicativo foi desenvolvido como parte da disciplina de **Programação Mobile** no curso de **Análise e Desenvolvimento de Sistemas - 3º semestre - FECAP**.

O app tem como objetivo **simular o pedido em uma pizzaria**, onde o usuário pode escolher o tipo de pizza, o tamanho e o método de pagamento. O valor do pedido é calculado com base na combinação escolhida. Após a seleção, o app exibe um resumo detalhado do pedido, incluindo o tipo de pizza, tamanho, método de pagamento e o valor total.

---

## Desenvolvedor

- **Nome:** Deivid Gomes de Oliveira  
- **Curso:** Análise e Desenvolvimento de Sistemas  
- **Semestre:** 3º  
- **Instituição:** FECAP  
- **Disciplina:** Programação Mobile  
- **Professor:** Vinícius Heltai  

---

## Tecnologias e Componentes Utilizados

- **Java**  
- **Android Studio**  
- **Layouts em XML**  
- **Navegação entre Activities com `Intent` + `Bundle`**  
- **Componentes Android:**
  - `CheckBox`, `RadioGroup`, `TextView`, `Button`, `RadioButton`

---

## Funcionalidades e Fluxo de Navegação

1. **Activity 1 – Seleção de Pizza**
   - O usuário escolhe o tipo de pizza (ex: Calabresa, Marguerita, Portuguesa) usando `CheckBoxes`.
   - O usuário pode selecionar um ou mais tipos de pizza.

2. **Activity 2 – Seleção de Tamanho e Pagamento**
   - O usuário seleciona o tamanho da pizza usando `RadioButton` (Pequena, Média, Grande).
   - O usuário escolhe o método de pagamento (Dinheiro ou Cartão) com `RadioButton`.

3. **Activity 3 – Resumo do Pedido**
   - O app exibe o resumo do pedido com as escolhas feitas pelo usuário: tipo(s) de pizza, tamanho, método de pagamento e o valor total calculado.
   - O resumo inclui um `TextView` dinâmico com todos os detalhes do pedido.
   - O valor final é calculado com base no tipo de pizza e no tamanho selecionado.
   - Há um botão para retornar à tela de seleção e refazer o pedido.

---

## Requisitos Atendidos

- ✅ Uso de **CheckBox** para seleção do tipo de pizza.
- ✅ Uso de **RadioGroup** e **RadioButton** para seleção do tamanho e método de pagamento.
- ✅ Exibição de **TextView** dinâmico para mostrar o resumo do pedido.
- ✅ Cálculo do valor total do pedido baseado na combinação de tipo de pizza, tamanho e método de pagamento.
- ✅ Navegação entre **3 Activities**:
  - Seleção de tipo de pizza.
  - Seleção de tamanho e pagamento.
  - Resumo do pedido.

---

## Desafios e Decisões no Desenvolvimento

- **Cálculo do Valor:** A lógica para calcular o valor do pedido foi implementada com base nas escolhas do usuário, considerando o preço de cada tipo de pizza e o preço associado ao tamanho.
  
- **Usabilidade:** Busquei garantir que a navegação entre as telas fosse simples e intuitiva, com uma interface limpa e objetiva.

- **Design:** A interface visual foi pensada para ser direta e prática, com elementos de interação fáceis de usar.

---

## Executável

- **APK gerado:** `pedidoPizza.apk`  
- **Projeto completo disponível em formato .zip**
