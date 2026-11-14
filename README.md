# CaveBuildLoja

Loja de texturas do jogo Cavebuild (https://lucasrfmiele13-afk.github.io/CaveBuild/).

O jogo lê o arquivo `index.json` deste repositório. As imagens ficam em `packs/`.

## Como adicionar uma textura
1. Crie uma pasta em `packs/`, por exemplo `packs/minha-textura/`.
2. Coloque um PNG 16x16 para cada bloco, com o número do bloco no nome (`4.png` para Pedra).
3. Adicione a textura em `index.json`, dentro de `packs`:

```json
{
  "name": "Minha textura",
  "author": "Seu nome",
  "desc": "Descrição curta.",
  "blocks": {
    "4": "packs/minha-textura/4.png"
  }
}
```

Números dos blocos: 0 Água, 1 Areia, 2 Grama, 4 Pedra, 5 Chão, 6 Parede de madeira, 7 Parede de pedra, 8 Terra, 9 Terra arada, 11 Cama, 17 Tronco, 23 Baú, 28 Minério de carvão, 29 Minério de cobre, 30 Minério de ferro, 31 Minério de ouro, 32 Minério de diamante, 33 Pedra preta.
