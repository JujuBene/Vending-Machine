<p align="center">
<img 
    src="./assets/capa.png"
    width="300"
/>

</p>

# Projeto Vending Machine (AFD)


 > ℹ️ **NOTE:** Este documento foi estruturado a partir da documentação do projeto “Vending Machine (Case 1)”, com o objetivo de organizar e facilitar a compreensão e reprodução do sistema baseado em Autômato Finito Determinístico (AFD).

Projeto com o objetivo de modelar e simular o funcionamento de uma máquina de venda automática de doces, utilizando conceitos de Teoria da Computação e Linguagens Formais, com foco em estados, transições e validações determinísticas.


## 💻 Tecnologias utilizadas no projeto

- Java (ou linguagem utilizada na implementação)
- Conceitos de Autômatos Finitos Determinísticos (AFD)
- Interface gráfica 
- Lógica de programação estruturada


## ✨ Como foi feito ?

Modelagem do sistema:
- Definição formal de um AFD com estados, alfabeto, estado inicial e estados finais.

Definição de estados:
- Foram criados estados representando cada etapa do processo:
- Inserção de dinheiro
- Seleção de produto
- Confirmação
- Processamento
- Entrega
- Finalização ou cancelamento

Transições:
- Implementação das regras determinísticas que controlam o fluxo da máquina, garantindo que o sistema nunca entre em estados inválidos.

Interface:
- Desenvolvimento de elementos visuais como:
- Display de status (LED simulado)
- Feedback de seleção
- Indicação de produtos disponíveis
- Simulação da entrega do produto

Validações:
- Controle de:
- Saldo do usuário
- Disponibilidade de estoque
- Cancelamento da operação
- Devolução de troco


## 🛠️ Instruções de execução

- 🤖 1. Inicialização do sistema
Inicie o programa — a máquina começará no estado inicial (Q0), aguardando inserção de dinheiro.
- 🤖 2. Inserção de dinheiro
Adicione valores permitidos (R$1, R$2 ou R$5), acumulando saldo.
- 🤖 3. Seleção do produto
Escolha um item disponível através do código correspondente.
- 🤖 4. Confirmação da compra
Confirme a operação para que o sistema valide saldo e estoque.
- 🤖 5. Processamento
Se válido → produto será entregue
Se inválido → operação finalizada com erro
- 🤖 6. Finalização
Após entrega ou cancelamento, o sistema retorna automaticamente ao estado inicial.


## 📌 Considerações finais

Este projeto demonstra na prática a aplicação de Autômatos Finitos Determinísticos, garantindo controle rigoroso de estados e transições. A modelagem assegura que todas as operações da máquina sejam previsíveis, seguras e consistentes, simulando fielmente o comportamento de uma vending machine real.


## 👨‍💻 Expert

<p>
    <p>&nbsp&nbsp&nbspJuliana Benedetti<br>
    &nbsp&nbsp&nbsp
    <a 
        href="https://github.com/JujuBene">
        GitHub
    </a>
    &nbsp;|&nbsp;
    <a 
        href="https://www.linkedin.com/in/juliana-magiero-benedetti/">
        LinkedIn
    </a>
 
   
   
</p>
<br/><br/>
<p>

---

