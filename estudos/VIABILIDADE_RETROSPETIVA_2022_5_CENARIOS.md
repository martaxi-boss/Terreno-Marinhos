# Estudo retrospetivo 2022 - alternativas de implantação, art. 14883

**Terreno:** art. urbano 14883, Troto / Igreja, Almancil (Loulé). **Área:** 3 285 m². **Armazém registado:** 253 m², legalidade urbanística não certificada. **Parcela excluída:** 14868 (1 327 m²).

Esta análise refere-se exclusivamente às regras conhecidas em **25/08/2022**, data da resposta CML no âmbito do direito à informação, processo 38/22. Não pressupõe que as regras estejam aplicáveis em 2026.

## Cenários para pedido de viabilidade — não aprovados

| Código | Intervenção | Fogos T1 | Construção de habitação | Armazém | Descrição |
|---|---|---:|---:|---|---|
| A | 3 lotes: 1 armazém + 2 habitacionais | 2 | 120 m² | Manter 253 m² | 2 T1 térreos de 60 m²; distribuição aritmética 1 400 + 650 + 650 m², resto 585 m² |
| B | Loteamento de 3 lotes | 3 | 180 m² | Demolir | 3 T1 isolados térreos de 60 m² |
| C | Loteamento de 4 lotes com geminação | 4 | 240 m² | Demolir | 2 pares de geminadas T1 com 60 m² totais por fogo em R/C + primeiro andar |
| D | Edifício único plurifamiliar | 4 | 240 m² + comuns | Demolir | 2 T1 por piso, 2 pisos, sem 4 lotes independentes |
| E | Loteamento de 4 lotes separados | 4 | 240 m² | Demolir | Alternativa com T1 térreos isolados sobre o desenho fotointerpretado, áreas 762/938/582/520 m² e via indicativa de 483 m² |

**Nota:** A proposta E foi produzida num desenho anterior e é distinta de B, C e D. As áreas apresentadas são ilustrativas, não parcelamento topográfico e nem limites certificados. 

## Regras a confrontar com o PDM em vigor em 2022

1. Artigo 27.º do PDM Loulé (Aviso 7430/2017): densidade até **50 habitantes/ha**, COS até **0,20**, sem comprometer futura estruturação urbana.
2. Em loteamento/destaque: frente mínima **10 m confinante com arruamento público** por lote/parcela restante. Não basta uma passagem privada.
3. Regime de construções isoladas (art. 27.º/3.2) não é direito de 450 m² por lote: implantação até **300 m²**, área de construção até **450 m²**, **dois pisos/6,5 m** e afastamentos gerais de 5 m, conforme condições e exceções. Não presumir aplicação automática a conjuntos plurifamiliares.
4. Referência de **3,2 habitantes por fogo** no cálculo de densidade da época. A CML decide o denominador para área residencial homogénea: não assumir toda a área de 3 285 m² como residencial.
5. RGEU aplicável em 2022: para T1 novo a referência mínima bruta era **52 m²**; os desenhos usam **60 m²**. Reduzir 60 para 35/40 m² não aumenta o número máximo de fogos pelo parâmetro de densidade.
6. Armazém: registo/caderneta não substituem prova de licença, antiguidade ou regularidade urbanística. Não demolir previamente sem confirmar direitos.
7. Pareceres e restrições: EN125/Infraestruturas de Portugal, linha de água/APA, eletricidade/E-Redes, servidão do aeroporto de Faro, vias municipais, acessibilidades, saneamento e cedências.

## Evidência Ferrari

O **Ferrari na VPS** executou efetivamente um compilador Typst privado e gerou o relatório PDF de quatro cenários:

- Pedido: https://github.com/martaxi-boss/VPS/blob/main/ferrari-requests/job-matinhos-2022-4cenarios-20261107-a.json
- Execução: [GitHub Actions #42337408212](https://github.com/martaxi-boss/VPS/actions/runs/42337408212), FERRARI_SKILL_JOB_STATUS=completed, FERRARI_SKILL_END_TO_END=PASS, artefacto ferrari-skill-result-42337408212, report.json.status=completed e PDF real artifacts/typst-document.pdf.
- O infográfico conceptual e as plantas de estudo anteriores **não foram executados pelo Ferrari**; apenas o PDF de memória técnica foi gerado pelo Ferrari e posteriormente integrado num caderno local para leitura.

## Limites e fontes

O ofício municipal de 2022 é **direito à informação do art. 110.º RJUE** e não aprova qualquer destes cenários. A ausência de levantamento topográfico original impede demonstrar frentes viárias, geometria exata, recuos, estacionamentos e servidões. O estudo não constitui um PIP formal.

Fontes: [PDM Loulé publicado em 2017, art. 27.º](https://diariodarepublica.pt/dr/detalhe/aviso/7430-2017-107617677); [PDM CML (PDF)](https://geoloule.cm-loule.pt/docs/regulamentos/pmots/PDM_Regulamento.pdf); [RGEU art. 67.º](https://diariodarepublica.pt/dr/legislacao-consolidada/decreto-lei/1951-120610500-201155054).

Atualizado em 07/11/2026.
