# Convite Navictur · 30 anos

Convite digital para a manhã de experiências dos 30 anos da Navictur
(check-in, treino Wolfit e café da manhã à beira-mar, no Estaleiro).

## Experiência
1. **Passaporte**: capa azul com o "30" dourado; ao tocar, abre como um livro com "Você foi convidada"
2. **Amanhecer no mar**: sol nascendo, ondas e um avião cruzando o céu
3. **Visto**: página de identificação com o nome da convidada e carimbos que "batem" na tela
4. **Carta** da equipe Navictur
5. **Roteiro**: a rota se desenha com a rolagem (check-in → Wolfit → café da manhã)
6. **Última chamada**: contagem regressiva até o fim do prazo de confirmação
7. **Destino**: cartão-postal com endereço e botão "Como chegar"
8. **Bagagem de mão**: etiquetas com o que levar
9. **Cartão de embarque**: confirmação que abre o WhatsApp com a mensagem pronta e carimba "CONFIRMADO"

Tipografia: Cinzel (títulos e rótulos), Cormorant Garamond (textos) e Pinyon Script (detalhes caligráficos).

## Como editar
Todos os dados ficam no objeto `CONFIG` no fim do `index.html`:
data, horário, local, endereço, link do Maps, número de WhatsApp que recebe as confirmações e prazo.
Os textos (carta, roteiro, bagagem) estão direto no HTML e podem ser trocados livremente.

## Link personalizado
Adicione `?nome=` ao link de cada convidada, por exemplo `https://seu-dominio/?nome=Maria%20Silva`.
O nome aparece na abertura, no visto, na carta e já vem preenchido no formulário.

## Publicar
Site estático (só `index.html` + `assets/`). Importe o repositório na Vercel sem build,
ou abra o `index.html` no navegador.
