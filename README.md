# Desempenho Operacional e de Corridas

## 1. Frequência de Corridas

### Horários de Pico
A maior frequência de corridas ocorre nos períodos de pico da tarde e início da noite, especificamente entre 16h00 e 20h00, com o ponto máximo às 18h00, superando 12.000 corridas. Há um segundo pico na parte da manhã, entre 9h00 e 11h00.

<img width="469" height="352" alt="image" src="https://github.com/user-attachments/assets/9f321c58-a464-4e48-8b31-e4650e586521" />

### Distribuição por Dia da Semana
A distribuição de corridas por dia da semana é quase uniforme, com pequenas variações. Os dias com maior volume percentual são:

- **Sábado e Segunda-feira**: 14.4% cada
- **Domingo, Terça-feira, Quarta-feira e Sexta-feira**: 14.3% cada
- **Quinta-feira**: 14.1%

  <img width="469" height="352" alt="image" src="https://github.com/user-attachments/assets/33989631-971d-4c09-a9fc-d0af37a03a20" />

## 2. Cancelamentos e Taxa de Conclusão

### Dias com Mais Cancelamentos
O gráfico "Quantidade de Cancelamentos por Dia da Semana" indica que o número de cancelamentos, tanto por motorista quanto por cliente, é consistente em todos os dias da semana, seguindo o volume de corridas.

<img width="469" height="402" alt="image" src="https://github.com/user-attachments/assets/3bceb23b-bebd-4237-b4cc-d20bb4a39312" />


### Taxas de Cancelamento
- **Percentual Canceladas pelo Cliente**: 7.00%
- **Percentual Canceladas pelo Motorista**: 18.00%
- **Viagens Incompletas**: 9.000

A taxa de cancelamento pelo motorista (18.00%) é mais do que o dobro da taxa de cancelamento pelo cliente (7.00%), sugerindo uma necessidade de investigação e mitigação de fatores que levam os motoristas a cancelar.

### Taxa de Conclusão de Viagens
A Taxa de Conclusão de Viagens é de **62.00%**. Este valor indica que quase 40% das solicitações de viagem não são concluídas (incluindo cancelamentos por motorista, cliente e viagens incompletas), o que representa uma oportunidade significativa para aumentar a eficiência operacional e a satisfação do cliente.

## 3. Motivos de Cancelamento
| Parte | Principal Motivo | Número de Cancelamentos |
|-------|------------------|------------------------|
| Cliente | Wrong Address (Endereço Errado) | 141.862 |
| Motorista | Customer related issue (Problema relacionado ao Cliente) | 129.837 |

### Motivos do Cliente
O motivo "Wrong Address" é o principal e esmagadoramente dominante, com 141.862 cancelamentos, muito superior aos demais (que estão na casa dos 1 a 2 mil), indicando um problema na precisão da localização de embarque ou no processo de inserção do endereço pelo usuário.

<img width="634" height="360" alt="image" src="https://github.com/user-attachments/assets/b30c3e5b-a94b-4d57-8b52-d360a913c235" />

### Motivos do Motorista
"Customer related issue" é o principal motivo de cancelamento pelos motoristas, com 129.837 ocorrências, o que é um termo vago e exige análise mais profunda para identificar a causa raiz. Outros motivos notáveis incluem problemas de saúde do cliente ("The customer was coughing/sick") e excesso de pessoas ("More than permitted people in there").

<img width="634" height="360" alt="image" src="https://github.com/user-attachments/assets/a8bf3a16-0eb7-49e3-8e25-8e35e174d6e1" />

## 4. Métricas de Tempo

### Média VTAT (Vehicle Time to Arrival): 8.45
O VTAT (Tempo de Chegada do Veículo) é o tempo que o motorista leva para chegar ao local de embarque após aceitar a corrida. A média de 8.45 minutos é uma métrica chave para a experiência do cliente e deve ser monitorada para garantir que os tempos de espera sejam competitivos.

### Média CTAT (Customer Time to Accept Trip): 29.04
O CTAT (Tempo do Cliente para Aceitar a Viagem) refere-se ao tempo que o cliente gasta para confirmar a solicitação após a correspondência com o motorista, ou, alternativamente, o tempo que o cliente gasta após a solicitação até que a viagem seja aceita. A média de 29.04 minutos é um valor significativamente alto para o processo de aceitação/confirmação em serviços de transporte por aplicativo, sugerindo que a definição desta métrica pode ser diferente do habitual (talvez o tempo total desde a solicitação até a aceitação do motorista) ou que o tempo de espera por um motorista aceitar é muito longo, impactando negativamente a experiência.

## 5. Localização e Tipos de Veículo

### Locais de Embarque e Rotas

#### Top 10 Locais de Pickup

<img width="533" height="356" alt="image" src="https://github.com/user-attachments/assets/7bb967d8-6d5a-4cae-bfa4-97174ebe711a" />

Os locais com mais embarques são liderados por:
1. **Khandsa** (949)
2. **Barakhamba Road** (946)
3. **Saket**
4. **Badarpur**
5. **Pragati Maidan**
6. E outros...

Estes locais representam áreas de alta demanda onde a disponibilidade de motoristas deve ser priorizada.

#### Distância Média e Rotas

<img width="617" height="338" alt="image" src="https://github.com/user-attachments/assets/958294a0-d290-4584-b772-d874a97dd82e" />

- **Distância Média por Corrida**: 24.34 km, indicando que a maioria das viagens é de médias a longas distâncias.
- As rotas mais frequentes (Top 10) demonstram conexões entre diferentes cidades/bairros (ex: DLF City Court -> Bhiwadi, Akshardham -> RK Puram, Janakpuri -> Faridabad Sector 15), reforçando o perfil de viagens de longa distância/interbairros ou intercidades.

### Tipo de Veículo
**Veículos Mais Usados**:

<img width="469" height="414" alt="image" src="https://github.com/user-attachments/assets/6bf4c183-b965-4bdd-ad40-44d3b5e4abde" />

- **"Auto"** (provavelmente Auto-Riquexá ou Tuk-Tuk): ~37.000 viagens
- **"Go Mini"**: ~30.000 viagens
- **"Go Sedan"**: ~27.000 viagens

Este dado é crucial para a gestão da frota e a estratégia de mercado, indicando a popularidade de veículos menores e mais econômicos.

## 6. Finanças e Pagamentos

### Método de Pagamento e Receita

#### Método de Pagamento Mais Usado
O **UPI** é o método de pagamento predominante, com quase 90.000 ocorrências, superando o "Cash" (cerca de 25.000).

<img width="468" height="399" alt="image" src="https://github.com/user-attachments/assets/af1532fb-dd3d-4cfc-8a31-9ca595928516" />

**O que é UPI?** UPI (Unified Payments Interface) é um sistema de pagamento instantâneo em tempo real desenvolvido pela National Payments Corporation of India (NPCI). Permite a transferência de fundos entre duas contas bancárias através de um aplicativo móvel. É extremamente popular na Índia devido à sua facilidade e conveniência.

#### Métricas Financeiras (Ano 2024)
- **Valor Médio por Viagem**: 478.12
- **Receita Total (2024-01-01 a 2024-12-31)**: 71.718.183,00

## 7. Crescimento de Clientes

### Novos Clientes por Mês

<img width="482" height="374" alt="image" src="https://github.com/user-attachments/assets/d1b4ff78-56fe-4c97-9898-46384fcd9e8b" />

O gráfico de "Novos Clientes por Mês" mostra uma alta variabilidade mensal no número de novos clientes:

- O ano começa em alta (**Jan**: ~12.850)
- Sofre uma queda significativa em **Fevereiro** (mínimo: ~11.950)
- Se recupera em **Março**
- O pico de novos clientes ocorreu em **Julho** (~12.900)
- A tendência no final do ano é de queda, de **Outubro a Dezembro**

O crescimento mensal é volátil, mas os valores se mantêm numa faixa estreita (entre ~11.950 e ~12.900), sugerindo que os esforços de aquisição de clientes mantiveram um nível constante, mas sem crescimento explosivo.

## Conclusão e Recomendações

O relatório destaca a dominância do "Auto" e do UPI, e a uniformidade da demanda ao longo da semana e a concentração nos horários de pico (16h00 às 20h00). O principal desafio reside na baixa Taxa de Conclusão (62.00%) e nas altas taxas de cancelamento, especialmente pelo motorista (18.00%).

### Recomendações Chave

1. **Redução de Cancelamentos por "Endereço Errado"**
   - Implementar melhorias na interface do usuário para a confirmação de endereços de embarque
   - Introduzir validação de geolocalização mais rigorosa

2. **Investigação de Cancelamentos do Motorista**
   - Conduzir uma análise aprofundada do motivo "Customer related issue" para identificar as causas subjacentes
   - Desenvolver intervenções (ex: suporte, treinamento, penalidades)

3. **Monitoramento do CTAT**
   - Investigar o alto CTAT (29.04 minutos), pois um longo tempo de espera por aceitação ou confirmação afeta diretamente a satisfação e retenção do cliente

4. **Otimização da Frota**
   - Manter a disponibilidade de veículos do tipo "Auto" e nos locais de alta demanda (Top 10 Locais de Pickup)
