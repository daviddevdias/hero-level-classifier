# Classificador de nível de herói

Exercício de lógica em JavaScript que percorre uma lista de heróis e classifica cada personagem pela quantidade de experiência (XP).

## 🚀 Executar

Requisito: Node.js instalado. Não há dependências externas.

```bash
git clone https://github.com/daviddevdias/hero-level-classifier.git
cd hero-level-classifier
node desafioDosHerois.js
```

## Regras implementadas

- Menor que 1.000: Ferro.
- 1.000 a 2.000: Bronze.
- 2.001 a 5.000: Prata.
- 5.001 a 7.000: Ouro.
- 7.001 a 8.000: Platina.
- 8.001 a 9.000: Ascendente.
- 9.001 a 10.000: Imortal.
- Acima de 10.000: Radiante.

Os intervalos descrevem os valores inteiros usados no exercício. A lista e os valores ficam em `desafioDosHerois.js`; não há entrada interativa nem validação de XP.

## Exemplo de saída

```text
O Herói de nome Goku está no nível de Platina
```

## 📁 Arquivos

- `desafioDosHerois.js`: classificador com arrays, objetos, laço e condicionais.
- `preçodaGasolina.js`: exercício adicional de cálculo, independente do classificador.

## 📌 Próximos passos

Extrair a classificação para uma função, validar valores de entrada e testar os limites de cada faixa.
