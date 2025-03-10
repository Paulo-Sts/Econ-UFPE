# Aula 13 - Sistemas Proporcionais  

## O que deve ser proporcionalmente representado nas câmaras baixas?  
- **Partidos?** -> Sistemas de listas partidárias  
  - **Lista Fechada** (África do Sul, Portugal)  
  - **Lista Aberta** (Finlândia, Brasil)  
  - **Lista Flexível** (Bélgica)  
- **Outros grupos?** -> STV (Sistema de voto único transferível)  
  - **Exemplo:** Irlanda, Malta  

### Exemplo
- Irlanda:  
  - Cada distrito elege **M** representantes (M>1).  
  - Cada partido apresenta até M candidatos por distrito.  
  - Eleitores dão **M votos ordenados**.  
  - Para ser eleito na primeira contagem, um candidato precisa atingir a **Cota Droop** (votos / (M+1)).  
  - Se ainda sobrarem cadeiras, os votos dos menos votados são transferidos sucessivamente.  
  - Se ainda houver vagas, os votos excedentes dos eleitos são redistribuídos conforme a 2ª preferência.  

## Sistemas de Listas  
- **M sempre maior que 1**.  
- Proporcionalidade perfeita é impossível (frações de cadeiras).  
- Fórmulas para distribuição de cadeiras entre listas partidárias:  
  - **Divisores** (D’Hondt, Sainte-Laguë).  
  - **Sobras** (Cota Hare, Cota Droop).  
  - Ordenação de candidatos:  
    - Fechada (partido define).  
    - Aberta (eleitor define).  
    - Flexível (partido + eleitor).  

### Exemplos de distribuição  
- **Cota Hare:** votos ÷ cadeiras disponíveis.  
- **D’Hondt:** divisão por 1, 2, 3, etc.  

### Exemplo: Brasil  
1. Soma dos votos em candidatos individuais + votos na legenda = **total de votos válidos** no distrito.  
2. Total de votos válidos ÷ cadeiras do distrito = **quociente eleitoral (cota Hare)**.  
3. Votos da lista (candidatos + legenda) ÷ quociente eleitoral = **quantidade de cadeiras para a lista**.  
4. Cadeiras excedentes distribuídas por **fórmula de divisores (similar ao método D’Hondt)**.  
5. Dentro de cada partido, os candidatos mais votados recebem as cadeiras conquistadas.  