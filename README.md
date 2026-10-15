# Convite Navictur · 30 anos

Convite digital em formato de passaporte para a manhã de experiências dos 30 anos da Navictur
(treino Wolfit + café da manhã com vista para o mar).

## Fluxo
1. Envelope-passaporte → "Toque para abrir" (o envelope abre e o mapa sobe)
2. Embarque: "30 anos juntos com a Navictur" + cartão de embarque com o nome da convidada
3. 01 · Página do passaporte (carimbos, dados do evento, faixa MRZ)
4. Painel de partidas com contagem regressiva
5. 02 · Nossa história
6. 03 · O destino (link para o Google Maps)
7. 04 · Roteiro (check-in, treino Wolfit, café da manhã)
8. 05 · Lista de viagem (o que vestir, o que levar, chegada)
9. Confirmação de presença: abre o WhatsApp com a mensagem pronta

## Como editar
Todos os dados ficam no objeto `CONFIG` no fim do `index.html`:
data/hora, local, endereço, link do Maps, **número de WhatsApp que recebe as confirmações**,
prazo de confirmação e o roteiro.

## Link personalizado
Adicione `?nome=` ao link para cada convidada:
`https://seu-dominio/?nome=Maria%20Silva` preenche o passaporte, o cartão de embarque e o formulário.

## Publicar
É um site estático (só `index.html` + `assets/`). Basta importar o repositório na Vercel
(sem build) ou abrir o `index.html` no navegador.
