# 🛒 TouchPay Intelligence - Demo

> Prova de Conceito (PoC) desenvolvida para o **Desafio AMLabs 2025**.

Este projeto é uma simulação funcional de interface para um totem de mercado autonomo, demonstrando como a **Inteligência de Venda Cruzada (Cross-Sell)** pode aumentar o Ticket Médio e a experiência do consumidor sem necessidade de novos hardwares.

🔗 https://kiarabarrios.github.io/sistema-de-pagamento-demo/

---

## 🎯 O Problema
Identificamos que o operador perde faturamento por dois motivos principais:
1.  **Esquecimento:** O cliente compra carvão mas esquece o sal grosso.
2.  **Passividade:** O totem atual é apenas um recebedor de pagamentos, não um vendedor ativo.

## 🚀 A Solução: TouchPay Intelligence
Implementamos um algoritmo leve de recomendação no Front-end que sugere produtos complementares no momento exato da decisão de compra.

### Funcionalidades da Demo:
* **Simulação de Scanner:** Clique nos produtos para simular o "bip" do código de barras.
* **Algoritmo de Associação:**
    * Se `Carvão` -> Sugere `Sal Grosso`.
    * Se `Cerveja` -> Sugere `Amendoim` ou `Salame` (Múltipla escolha).
    * Se `Espaguete` -> Sugere Combo `Molho + Queijo` (Seleção inteligente).
* **Gestão de Carrinho:** Agrupamento de itens e cálculo em tempo real.
* **UX/UI:** Interface fiel à identidade visual da AMLabs (Azul/Branco) e responsiva.

---

## 🛠️ Viabilidade Técnica
A solução foi construída pensando na infraestrutura atual da AMLabs:

* **Stack:** HTML5, CSS3 e Vanilla JavaScript (Sem frameworks pesados).
* **Compatibilidade:** Roda em qualquer navegador web e é compatível com o sistema operacional dos Totens SK210 e TP Flex.
* **Performance:** Código otimizado, sem dependências externas, garantindo velocidade no carregamento.

---

## 💰 Viabilidade Econômica (ROI)
* **Custo de Hardware:** R$ 0,00 (Utiliza o equipamento já instalado).
* **Implementação:** Atualização de Software via OTA (Over-the-air).
* **Impacto:** Aumento direto no Ticket Médio através de compras por impulso induzido.

---

### Como rodar localmente
1. Clone este repositório.
2. Abra o arquivo `index.html` em seu navegador.

---
Desenvolvido pela equipe do Desafio AMLabs 2025. 🚀
