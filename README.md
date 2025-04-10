
# 🚛 Calculadora de Prejuízo de Carga e Frete 💰

## 🌟 O que é isso?

Oi! Esse é um projetinho web super legal que eu criei pra calcular o **prejuízo** em operações de carga e frete. Ele usa valores como peso total, valor total, peso descarregado, frete da empresa e frete por tonelada pra te ajudar a entender quanto você perdeu (ou não!). Tudo é atualizado na hora, tipo mágica! ✨

Funciona direitinho no computador 💻 e no celular 📱, com uma carinha simples e resultados em reais (R$). É pra quem quer uma ferramenta prática pra analisar transporte de cargas sem dor de cabeça!

## 🎉 O que ele faz?

- **🚚 Prejuízo da Carga**:
  - Calcula a diferença: Peso Total - Peso Descarregado.
  - Descobre o valor por unidade: Valor Total ÷ Peso Total.
  - Mostra o prejuízo: Diferença × Valor Unitário.
- **🚐 Prejuízo do Frete**:
  - Calcula o frete a cobrar: Peso Descarregado × Frete P/Ton ÷ 1000.
  - Mostra o prejuízo: Frete Empresa - Frete a ser cobrado.
- **✏️ Campos que você pode mudar**:
  - Peso Total (Carga e Frete), Valor Total, Peso Descarregado, Frete Empresa e Frete P/Ton.
- **💸 Dinheiro bonitinho**: Prejuízos aparecem como "R$ 1234.56".
- **📏 Se adapta ao tamanho da tela**: Tabelas lado a lado no PC, empilhadas no celular.
- **👋 Rodapé**: Meu nome (Gabriel Belitz Baldez) com links pro LinkedIn e GitHub!

## 🛠️ Como foi feito?

- **HTML5** 📝: A base de tudo, tipo o esqueleto da página.
- **CSS3** 🎨: Deixa tudo bonito e arrumadinho, com truques pra telas pequenas.
- **JavaScript** ⚡: Faz os cálculos voarem e atualiza tudo na hora!

## 🚀 Como usar?

1. Abra o arquivo `index.html` no seu navegador favorito (Chrome, Firefox, etc.).
2. Na parte "Cálculo de Prejuízo CARGA" 🚚:
   - Digite ou mude "Peso Total", "Valor Total" e "Peso Descarregado".
   - Veja "Diferença", "Valor Unitário" e "Prejuízo" mudarem sozinhos!
3. Na parte "Cálculo de Prejuízo FRETE" 🚐:
   - Digite ou mude "Frete Empresa", "Peso Total", "Frete P/Ton" e "Peso Descarregado".
   - Confira "Frete a ser cobrado" e "Prejuízo" atualizando na hora!
4. Os prejuízos aparecem como "R$" pra ficar fácil de entender. 💰

## 🎲 Exemplo pra testar

- **Carga**:
  - Peso Total: `49620`
  - Valor Total: `118674.5`
  - Peso Descarregado: `24740`
  - Resultado: Prejuízo ≈ **R$ 59504.67**
- **Frete**:
  - Frete Empresa: `12901.2`
  - Peso Descarregado: `24740`
  - Frete P/Ton: `260`
  - Resultado: Prejuízo ≈ **R$ 6468.80**

## 📂 O que tem dentro?

- **`index.html`**: Tudo mora aqui!
  - **HTML** 📝: Tabelas e rodapé.
  - **CSS** 🎨: Estilos + adaptação pra celular (muda em 768px).
  - **JavaScript** ⚡: Funções `formatarDinheiro` (pra R$) e `atualizarCalculos` (faz as contas).

## 👨‍💻 Quem fez?

Eu! **Gabriel Belitz Baldez** 😊
- 🔗 [LinkedIn](https://www.linkedin.com/in/gabriel-baldez-6a7847217/)
- 🐙 [GitHub](https://github.com/GabrielBBaldez)

Gostou? Usa à vontade e me conta o que achou! 🚀
