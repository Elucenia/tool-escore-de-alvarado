<!-- ELUCENIA technical documentation · escore-de-alvarado · pt-BR · no clinical/professional/rights approval -->

# Escore de Alvarado

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/escore-de-alvarado)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Migração da dor para a fossa ilíaca direita

`migra`

### Anorexia (ou acetona na urina)

`anorex`

### Náuseas ou vômitos

`nausea`

### Dor à palpação da fossa ilíaca direita

`dor`

### Descompressão brusca dolorosa (Blumberg)

`desc`

### Temperatura ≥ 37,3 °C

`febre`

### Leucocitose \> 10.000/mm³

`leuco`

### Desvio à esquerda (neutrófilos \> 75%)

`desvio`

## Edição do método

Alvarado 1986:MANTRELS 8 itens,0–10; versão comdesvioesquerda

## Fórmula documentada

MANTRELS: Migração da dor (1), Anorexia (1), Náuseas/vômitos (1), Tenderness (dor) na fossa ilíaca direita (2), Rebound (descompressão dolorosa, 1), Elevação da temperatura (1), Leucocitose (2) e Shift (desvio à esquerda, 1). Total de 0 a 10.

## Limites e população

O Alvarado 1986 foi elaborado a partir de 305 pacientes hospitalizados com dor abdominal sugestiva de apendicite e oito fatores clínicos/laboratoriais. O resumo original não valida automaticamente diferentes faixas etárias, gestantes ou estratégias de alta/imagem. Os limiares de decisão e a população da versão usada devem ser conferidos separadamente; a ferramenta implementa a variante que inclui desvio à esquerda.

## Referências

- [Alvarado A. A practical score for the early diagnosis of acute appendicitis. Ann Emerg Med, 1986.](https://doi.org/10.1016/S0196-0644(86)80993-3)

- [Di Saverio S et al. Diagnosis and treatment of acute appendicitis: 2020 update of the WSES Jerusalem guidelines. World J Emerg Surg, 2020.](https://doi.org/10.1186/s13017-020-00306-3)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

As informações abaixo preservam as saídas do método para exemplos sintéticos. Não constituem validação clínica independente.

### 1

Apendicite improvável (0 a 4)

Considerar outras causas; reavaliar se os sintomas persistirem.


### 2

Compatível com apendicite (5 a 6)

Observação e reavaliação seriada ou exame de imagem.


### 3

Apendicite provável (7 a 8)

Avaliação cirúrgica; imagem conforme o perfil do paciente.


### 4

Apendicite muito provável (9 a 10)

Avaliação cirúrgica.

