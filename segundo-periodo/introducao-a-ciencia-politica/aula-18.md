# Aula 18: Sistemas Partidários 2 - Variáveis (Referência: Bardi e Mair (2010[2008]))

## Como os Sistemas Partidários Variam?
- **Como se distinguem uns dos outros?**
- **Como mudam no tempo?**

**Variáveis**:
1. **Fragmentação**.
2. **Polarização**.
3. **Institucionalização**.
4. **Nacionalização**.

## Tamanho x Distribuição Ideológica (Sartori 1982[1976])

| Contagem | **Polarizado** | **Moderado** |
|----------|----------------|--------------|
| **2**    | –              | Coalizões são desnecessárias, [expectativa razoável de] alternância no poder. |
| **3 a 5** | –              | Governo de coalizão, dinâmica bipolar entre coalizões, competição centrípeta, política moderada, oposição unilateral, pequena distância ideológica. |
| **> 5**  | Partidos anti-sistema relevantes, partido(s) no centro e oposições bilaterais, competição centrífuga e ideológica, oposições irresponsáveis, promessas levianas. | – |

## Fragmentação (Eleitoral ou Parlamentar)
- **Laakso e Taagepera (1979)**:
  - **Número Efetivo de Partidos** = \( 1 / \sum p_i^2 \).
- **Rae (1967)**:
  - **Fracionalização Partidária** = \( 1 - \sum p_i^2 \).

### Exemplo: Fragmentação no Peru (2011)

| Partido    | %   | Prop  | Quadrado |
|------------|-----|-------|----------|
| GANA PERU    | 25,27  | 0,2527  | 0,06  |
| FUERZA 2011    | 22,97  | 0,2297  | 0,05  |
| PERU POSIBLE    | 14,83  | 0,1483  | 0,02  |
| ALIANZA POR EL GRAN CAMBIO | 14,42  | 0,1442  | 0,02  |
| ALIANZA SOLIDARIDAD NACIONAL | 10,22  | 0,1022  | 0,01  |
| PARTIDO APRISTA PERUANO | 6,43  | 0,0643  | 0,00  |
| CAMBIO RADICAL    | 2,71  | 0,0271  | 0,00  |
| FONAVISTAS DEL PERU    | 1,32  | 0,0132  | 0,00  |
| PARTIDO DESCENTRALISTA FUERZA SOCIAL | 0,84  | 0,0084  | 0,00  |
| ADELANTE    | 0,33  | 0,0033  | 0,00  |
| FUERZA NACIONAL    | 0,29  | 0,0029  | 0,00  |
| DESPERTAR NACIONAL    | 0,24  | 0,0024  | 0,00  |
| JUSTICIA, TECNOLOGIA, ECOLOGIA | 0,14  | 0,0014  | 0,00  |
| **Total**    | 100,00  | 1,0000  | 0,17  |

\[ \text{NEP} = 1 / 0.17 = 5.71 \]

**Fracionalização** = \( 1 - 0.17 = 0.83 \).

## Polarização (Dalton 2008)

### Posicionamento dos Cidadãos na Escala Esquerda-Direita
- **Canadá**:
  - 1 a 9.
- **Espanha**:
  - 1 a 9.
- **Eslovênia**:
  - 1 a 9.
- **República Tcheca (2002)**:
  - 1 a 9.

### Índice de Polarização

\[ \text{Índice de Polarização} = \sqrt{\sum p_i \cdot \left(\frac{ps_i - sa}{5}\right)^2} \]

Onde:
- \( p_i \) = % de votos (ou cadeiras) do partido \( i \).
- \( ps_i \) = posição do partido \( i \) na escala.
- \( sa \) = média do sistema.

**Interpretação**:
- **0**: Todos os partidos na mesma posição.
- **10**: Todos os partidos divididos entre os extremos.

**Cuidado**: Polarização do sistema partidário ≠ polarização afetiva.

### Exemplo de Cálculo de Polarização

| Partido | Posição do Partido \( i \) | % do Partido \( i \) | Posição do Partido \( i \) – Média do Sistema [6,1] | \(\left(\frac{ps_i - sa}{5}\right)^2\) | \( p_i \cdot \left(\frac{ps_i - sa}{5}\right)^2 \) |
|---------|----------------------------|----------------------|----------------------------------------------------|----------------------------------------|----------------------------------------------------|
| A       | 1,9                        | 2,4                  | -4,19                                              | 0,70                                   | 1,68                                               |
| B       | 2,3                        | 3,1                  | -3,83                                              | 0,59                                   | 1,82                                               |
| C       | 3,5                        | 5,5                  | -2,55                                              | 0,26                                   | 1,42                                               |
| D       | 3,6                        | 1,4                  | -2,46                                              | 0,24                                   | 0,33                                               |
| E       | 5,2                        | 23,5                 | -0,92                                              | 0,03                                   | 0,79                                               |
| F       | 6,5                        | 1,7                  | 0,40                                               | 0,01                                   | 0,01                                               |
| G       | 6,5                        | 1,5                  | 0,45                                               | 0,01                                   | 0,01                                               |
| H       | 6,9                        | 2,2                  | 0,80                                               | 0,03                                   | 0,06                                               |
| I       | 7,1                        | 0,6                  | 1,00                                               | 0,04                                   | 0,02                                               |
| J       | 7,1                        | 18,0                 | 1,00                                               | 0,04                                   | 0,72                                               |
| K       | 7,1                        | 1,9                  | 1,00                                               | 0,04                                   | 0,07                                               |
| L       | 7,1                        | 5,1                  | 1,00                                               | 0,04                                   | 0,20                                               |
| M       | 7,2                        | 2,8                  | 1,10                                               | 0,05                                   | 0,13                                               |
| N       | 7,2                        | 8,9                  | 1,10                                               | 0,05                                   | 0,43                                               |
| O       | 7,4                        | 2,1                  | 1,26                                               | 0,06                                   | 0,13                                               |
| P       | 7,4                        | 1,5                  | 1,30                                               | 0,07                                   | 0,10                                               |
| Q       | 7,6                        | 3,4                  | 1,50                                               | 0,09                                   | 0,31                                               |
| R       | 8,5                        | 4,3                  | 2,45                                               | 0,24                                   | 1,04                                               |
| **Média do Sistema** | 6,1                        | 100,0                |                                                    |                                        | **Soma** 9,30 **Raiz Quadrada** 3,05               |

## Institucionalização
**Precursor**: Mainwaring e Scully (1994).
- **Estabilidade da competição** (volatilidade eleitoral).
- **Raízes na sociedade** (voto ideológico).
- **Legitimidade conferida pelos atores políticos**.
- **Autonomia dos partidos em relação aos líderes**.

### Volatilidade Eleitoral (Pedersen 1979)

\[ \text{Volatilidade} = \frac{\sum |\Delta p_i|}{2} \]

Onde \( \Delta p_i \) é a diferença entre as votações obtidas pelo partido \( i \) em duas eleições consecutivas.

### Exemplo de Cálculo de Volatilidade

| Eleição 1    | Eleição 2    |
|--------------|--------------|
| **Partido**  | **%**        | **Partido** | **%**        | **Dif**      | **Módulo da Dif** |
| A            | 1,42         | A           | 0,00         | -1,42        | 1,42              |
| B            | 9,28         | B           | 14,14        | 4,85         | 4,85              |
| C            | 0,30         | C           | 0,30         | -0,01        | 0,01              |
| D            | 0,14         | D           | 0,03         | -0,10        | 0,10              |
| E            | 23,13        | E           | 24,97        | 1,84         | 1,84              |
| F            | 47,67        | F           | 37,55        | -10,12       | 10,12             |
| G            | 2,04         | G           | 3,93         | 1,89         | 1,89              |
| H            | 16,02        | H           | 19,08        | 3,07         | 3,07              |
| **Total**    | 100,00       | **Total**   | 100,00       | **Soma**     | 23,30             |

**Volatilidade** = \( \frac{23,30}{2} = 11,65 \).

## Nacionalização (Jones e Mainwaring 2003)

### Capilaridade/Dispersão Territorial do Desempenho Eleitoral

- **Nacionalização do Partido \( i \)** = \( 1 - \text{Gini da votação} \).
  - **Gini**: Mede concentração de renda, de 0 (renda igualmente distribuída entre grupos) a 1 (renda totalmente concentrada em um dos grupos).
- **Nacionalização do Sistema Partidário** = \( \sum \text{Nacionalização} \cdot \% \text{votação} \).

### Exemplo de Cálculo de Nacionalização

| Distritos | Votação do Partido A | Proporção | Proporção Acumulada | \( p. \text{acumulada} + p. \text{acumulada}_{i-1} \) |
|-----------|----------------------|-----------|---------------------|-------------------------------------------------------|
| Sul       | 1000                 | 0.025     | 0.025               | 0.025                                                 |
| Norte     | 1000                 | 0.025     | 0.050               | 0.075                                                 |
| Leste     | 2000                 | 0.050     | 0.100               | 0.150                                                 |
| Oeste     | 6000                 | 0.150     | 0.250               | 0.350                                                 |
| Centro    | 30000                | 0.750     | 1.000               | 1.250                                                 |
| **Total** | 40000                | 1.000     |                     | 1.850                                                 |

**Gini do Partido A** = \( 1 - \frac{1,850}{5} = 0,63 \).

**Nacionalização do Partido A** = \( 1 - 0,63 = 0,37 \).

### Nacionalização do Sistema Partidário

| Partido | Nacionalização do Partido | % Votos | Nacionalização \( p_i \cdot \% \text{votos} p_i \) |
|---------|---------------------------|---------|----------------------------------------------------|
| A       | 0.37                      | 76.92   | 28.46                                              |
| B       | 0.87                      | 23.08   | 20.00                                              |
| **Nacionalização do Sistema** |                           |         | **48.46**                                          |