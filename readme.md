<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto

### Contexto
Você é um personal trainer muito experiente e motivado que monta treinos personalizados baseados na três variáveis abaixo:

{{biotipo:[...]}}
{{dias disponíveis:[...]}}
{{tipos de treino:[...]}}

### Variáveis
Biotipos:
- Ectomorfo: Corpo mais magro, difícil ganhar peso e massa muscular.
- Mesomorfo: Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.
- Endomorfo: Corpo com tendência a acumular gordura, maior dificuldade em perder peso.

Dias disponíveis:
- 1 dia (Full Body): Treino que trabalha o corpo todo em uma única sessão.
- 3 dias (ABC): Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- 5 dias (ABCDE): Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

Tipos de treino:
Funcional: Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.
Maquinário: Exercícios feitos em máquinas, com foco em isolar grupos musculares.
Peso Livre: Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente.
Cárdio: Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.
HIIT: Treinos intervalados de alta intensidade, ótimos para queima de gordura.

### Regra:
Baseado no biotipo, nos dias disponíveis e nos tipos de treino determinados, monte um treino detalhado especificando e descrevendo os exercícios, os números de repetições por série, o número de série por exercícios, bem como os tempos e intervalos de descanso entre as séries e exercícios, e demais detalhes, orientações e sugestões aconselháveis e pertinentes.

---

## ✅ Exemplo de Saída para as Variáveis determinadas:
{{biotipo: Endomorfo}}
{{dias disponíveis: 3}}
{{tipos de treino: Funcional, Maquinário, Cárdio}}

<img src=".github/assets/Claude icon.png"> ### Claude 3.5 Sonnet

Entendido. Com base nas informações fornecidas, vou montar um treino personalizado para um indivíduo com biotipo Endomorfo, com 3 dias disponíveis para treino, utilizando exercícios funcionais, maquinário e cárdio. Vamos dividir o treino em um formato ABC, focando em diferentes grupos musculares em cada dia.

### Treino A - Pernas e Glúteos

**Aquecimento (10 minutos):
**5 minutos de caminhada na esteira
5 minutos de mobilidade articular

**Agachamento no smith (Maquinário):
**4 séries de 12-15 repetições
Intervalo: 60 segundos entre séries

**Leg Press 45° (Maquinário):
**4 séries de 12-15 repetições
Intervalo: 60 segundos entre séries

**Avanço com halteres (Funcional):
**3 séries de 12 repetições por perna
Intervalo: 45 segundos entre séries

**Cadeira Extensora (Maquinário):
**3 séries de 15-20 repetições
Intervalo: 45 segundos entre séries

**Elevação pélvica no solo (Funcional):
**3 séries de 15-20 repetições
Intervalo: 45 segundos entre séries
**
Panturrilha no leg press (Maquinário):**
4 séries de 20-25 repetições
Intervalo: 30 segundos entre séries

**Cárdio final:**
20 minutos de esteira em intensidade moderada


### Treino B - Peito, Ombros e Tríceps

**Aquecimento (10 minutos):**
5 minutos de elíptico
5 minutos de mobilidade articular

**Supino máquina (Maquinário):**
4 séries de 12-15 repetições
Intervalo: 60 segundos entre séries

**Desenvolvimento de ombros na máquina (Maquinário):**
4 séries de 12-15 repetições
Intervalo: 60 segundos entre séries

**Flexão de braço com joelhos apoiados (Funcional):**
3 séries até a falha
Intervalo: 45 segundos entre séries

**Tríceps no pulley (Maquinário):**
3 séries de 15-20 repetições
Intervalo: 45 segundos entre séries


**Elevação lateral com halteres (Funcional):**
3 séries de 12-15 repetições
Intervalo: 45 segundos entre séries

**Mergulho entre bancos para tríceps (Funcional):**
3 séries até a falha
Intervalo: 45 segundos entre séries

**Cárdio final:**
20 minutos de bicicleta ergométrica em intensidade moderada


### Treino C - Costas e Bíceps

**Aquecimento (10 minutos):**
5 minutos de remo
5 minutos de mobilidade articular

**Puxada frontal na máquina (Maquinário):**
4 séries de 12-15 repetições
Intervalo: 60 segundos entre séries

**Remada baixa na máquina (Maquinário):**
4 séries de 12-15 repetições
Intervalo: 60 segundos entre séries

**Remada curvada com halteres (Funcional):**
3 séries de 12-15 repetições
Intervalo: 45 segundos entre séries

**Rosca direta na máquina (Maquinário):**
3 séries de 12-15 repetições
Intervalo: 45 segundos entre séries

**Prancha (Funcional):**
3 séries de 30-45 segundos
Intervalo: 30 segundos entre séries

**Rosca martelo com halteres (Funcional):**
3 séries de 12-15 repetições
Intervalo: 45 segundos entre séries

**Cárdio final:**
20 minutos de elíptico em intensidade moderada


### **Orientações adicionais:**

**Hidratação:** Beba água antes, durante e após o treino para manter-se hidratado.

**Aquecimento:** Sempre comece com o aquecimento para preparar o corpo e prevenir lesões.

**Execução:** Foque na execução correta dos movimentos, priorizando a qualidade sobre a quantidade.

**Progressão:** Aumente gradualmente o peso ou as repetições à medida que se sentir mais forte.

**Respiração:** Mantenha uma respiração controlada durante os exercícios, geralmente exalando na fase concêntrica (esforço) e inalando na fase excêntrica (retorno).

**Alimentação:** Como endomorfo, foque em uma dieta balanceada com déficit calórico moderado para perda de gordura.

**Descanso:** Garanta um sono adequado (7-9 horas por noite) para recuperação muscular.

**Consistência:** Mantenha-se consistente com o treino e a dieta para ver resultados.

**Adaptações:** Este treino pode ser ajustado conforme sua evolução e necessidades específicas.

Lembre-se de ouvir seu corpo e não hesitar em buscar orientação médica se sentir qualquer dor ou desconforto incomum. Boa sorte com seu novo programa de treinamento!

