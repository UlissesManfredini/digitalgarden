---
{"dg-publish":true,"permalink":"/codex-and-cronicas/experiencia-e-niveis/","updated":"2025-10-28T00:37:56.050-03:00"}
---

# Sistema de Experiência Híbrida (versão atualizada)

O **Sistema de Experiência Orgânica** é um método híbrido de avanço de personagem que une os conceitos de **XP tradicional**, **milestones narrativos** e **multiplicadores dinâmicos**.  
A proposta é oferecer um progresso mais **natural, coerente e meritocrático**, recompensando o jogador não apenas por derrotar inimigos, mas também por suas **ações significativas, planos inteligentes e interações relevantes**.

---

## Conceito base

O ganho de XP é dividido em dois componentes:

1. **Pontos de Ação (PA)** — pontos dados a cada ação notável, divididos em categorias (combate, interação, exploração, etc.).
    
2. **Multiplicador de Impacto (MI)** — aplicado no final da sessão, ajusta o valor dos pontos conforme o **nível do personagem**, o **tipo de ação** e o **peso narrativo ou desafio**.
    

A soma desses fatores resulta em uma **experiência fluida e proporcional ao impacto real das ações**.

---

## Fórmulas gerais

### 1. Pontos de Combate (PCOMB)

Usado para qualquer situação em que o personagem derrota ou contribui para derrotar uma criatura.

$\text{PCOMB} = 5 \cdot n \cdot \left( \frac{CR \cdot 5}{0,25 \cdot n} \right)$


- **n** = nível atual do personagem
    
- **CR** = desafio da criatura (Challenge Rating)
    

> 💡 Em um combate **ideal**, onde o CR = 0,25 × nível do personagem,  
> o resultado simplifica para:
> 
> $PCOMB_{ideal} = 25 \cdot n$

---

### 2. Pontos de Interação (PINT)

Usado para **qualquer avanço não combativo**, como diplomacia, planejamento, investigação, exploração ou solução de desafios narrativos.

$P_{INT} = 5 \cdot n \cdot i$

- **n** = nível atual do personagem
    
- **i** = valor da interação (de **3 a 7**) conforme a **relevância narrativa**
    

|Tipo de interação|Valor **i**|
|---|---|
|Ação menor / social leve|3|
|Planejamento tático ou decisão importante|4|
|Descoberta relevante / avanço de trama|5|
|Solução criativa de desafio / puzzle|6|
|Marco narrativo ou virada de história|7|

> 💡 As ações não combativas sempre usam essa fórmula.  
> Exemplo: um personagem de nível 10 realiza uma decisão estratégica com **i = 4** → 5×10×4 = **200 XP**.

---

## Tabela de progressão de níveis (1–35)

A fórmula da progressão de XP foi ajustada para refletir **crescimento não linear** e **equilíbrio de recompensas** entre combate e outras ações.

$$
\text{XP}_{\text{para subir}} = \left\lceil \frac{25 \cdot n \cdot (n + 8)}{3} \right\rceil
$$

|Nível|XP para subir|XP acumulada|XP/combate ideal|Combates ideais p/ subir|
|---|---|---|---|---|
|1|75|0|25|3|
|2|167|75|50|3|
|3|275|242|75|4|
|4|400|517|100|4|
|5|542|917|125|4|
|6|700|1.459|150|5|
|7|875|2.159|175|5|
|8|1.067|3.034|200|6|
|9|1.275|4.101|225|6|
|10|1.500|5.376|250|6|
|11|1.742|6.876|275|7|
|12|2.000|8.618|300|7|
|13|2.275|10.618|325|7|
|14|2.567|12.893|350|8|
|15|2.875|15.460|375|8|
|16|3.200|18.335|400|8|
|17|3.542|21.535|425|9|
|18|3.900|25.077|450|9|
|19|4.275|28.977|475|9|
|20|4.667|33.252|500|10|
|21|5.075|37.919|525|10|
|22|5.500|42.994|550|10|
|23|5.942|48.494|575|11|
|24|6.400|54.436|600|11|
|25|6.875|60.836|625|11|
|26|7.367|67.711|650|12|
|27|7.875|75.078|675|12|
|28|8.400|82.953|700|12|
|29|8.942|91.353|725|13|
|30|9.500|100.295|750|13|
|31|10.075|109.795|775|13|
|32|10.667|119.870|800|14|
|33|11.275|130.537|825|14|
|34|11.900|141.812|850|14|
|35|12.542|153.712|875|15|

---

## Filosofia de design

- O sistema busca **recompensar a variedade de ações**, e não apenas o abate de monstros.
    
- O ganho de XP é **contínuo e modular**, permitindo que o Mestre atribua pontos em tempo real e aplique o multiplicador no fim da sessão.
    
- O crescimento é **não linear**, mas sempre “grounded”: evita saltos absurdos e mantém ritmo coerente com campanhas longas.
    
- Em níveis altos, o número de combates ideais necessários aumenta **lentamente** (aprox. +1 a cada 3 níveis).
    

---

## Sugestões de uso em mesa

- Ao longo da sessão, anote cada ação relevante com sua **tag** (combate, exploração, desafio, etc.).
    
- Ao final, aplique o **multiplicador de impacto** e registre o total de XP ganho.
    
- XP pode ser somada individualmente (para campanhas com papéis distintos) ou igualmente (para campanhas cooperativas).
    
- Evite usar o sistema como punição — o foco é **recompensar o envolvimento e a criatividade**, não apenas o sucesso mecânico.
    

---

## Versões e ajustes opcionais

- O Mestre pode reduzir o multiplicador base (de 5 para 4, por exemplo) para campanhas de ritmo mais lento.
    
- Interações repetitivas ou triviais não devem gerar pontos múltiplos — apenas ações de **impacto ou inovação**.
    
- Caso o grupo prefira simplicidade, é possível usar apenas **PCOMB e PINT**, ignorando o MI (aplicando-o apenas em eventos narrativos).
    

---

## Exemplo prático — sessão completa

**Personagem nível 5:**

- 2 combates contra CR 2 (combate ideal):  
    PCOMB = 2 × (5×5×(2×5)/(0,25×5)) = 2 × 1000 = **2000 XP**
    
- 1 interação diplomática importante (i = 5):  
    PINT = 5×5×5 = **125 XP**
    
- Total base = 2125 XP
    
- Multiplicador = (5×5) + 4 (interação importante) = **29**
    
- XP final = 2125 × 29 = **61.625 XP**  
    (dividido entre os membros do grupo ou conforme participação).
    

---

## Observações finais

- Este sistema é **totalmente compatível** com a _Progressão Orgânica_ — XP mede crescimento narrativo e técnico, enquanto Progressão Orgânica mede o **aperfeiçoamento prático** das habilidades.
    
- Juntos, os dois sistemas criam uma estrutura de evolução **natural, verossímil e flexível**, adequada para campanhas longas, narrativas e realistas.