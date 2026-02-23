### ⚔️ 1. Armas Corpo a Corpo (Dano Escalável)

Nesta categoria, o dano depende diretamente da perícia e do esforço físico do operador.

$$\text{Dano} = \text{Dado da Arma} + \text{Bônus de Atributo}$$

- **Atributo Principal:** Geralmente **Potência (FOR)**.
    
- **Acuidade:** Algumas armas (como a _Adaga de Plasma_) permitem usar **Reflexos (DEX)** se o personagem for ágil.
    
- **Lógica:** Representa o impacto físico. Se você é mais forte, seu golpe com o _Espadão de Cromo_ dói mais.
    

---

### 🏹 2. Armas à Distância e Tecnológicas (Dano Fixo)

Aqui, o que causa o estrago é a tecnologia (pólvora, plasma ou magnetismo), não a força de quem aperta o gatilho.

$$\text{Dano} = \text{Valor Fixo Alto (ex: 2d8, 1d12)}$$

- **Sem Somar Atributo:** Uma bala de rifle tem a mesma força saindo da mão de um gigante ou de uma criança.
    
- **Vantagem:** O dano base costuma ser bem maior que o das armas brancas.
    
- **Custo:** Exige munição limitada, manutenção cara e faz barulho (atrai inimigos).
    

---

### 📊 Tabela de Comparação Rápida

|**Tipo de Arma**|**Exemplo**|**Dano Típico**|**Vantagem**|
|---|---|---|---|
|**Curta**|Adaga de Plasma|$1d4 + \text{DEX}$|Leve e rápida.|
|**Média**|Espada de Sucata|$1d8 + \text{FOR}$|Equilibrada.|
|**Longa**|Martelo Hidráulico|$2d8 + \text{FOR}$|Destrói blindagem.|
|**Distância**|Fuzil de Trilho|$1d12$ (Fixo)|Alcance e perfuração.|
|**Área**|Canhão de Pulso|$2d10$ (Fixo)|Dano em cone (vários alvos).|

---
### **Dano de Radiação Abissal:**  Degradação de Estado.

| NIVEL 1 | Desvantagem em testes físicos (tosse, falta de ar, nausea)     |
| ------- | -------------------------------------------------------------- |
| NIVEL 2 | Redução de PV máximo em 50%                                    |
| NIVEL 3 | Morte. após 48hrs sobre efeito de radiação abissal você morre. |

---


### 🔩 O Fator Modding

- **Amplificador de Éter:** Adiciona $+2$ no dano final de reações.
    
- **Ponteira Perfurante:** Ignora a defesa (CA) do inimigo em vez de aumentar o dano bruto.

---

### 🎲 00_Dados_e_testes (Mecânicas Avançadas)

Nesta seção, definimos como o sistema trata os picos de performance (Críticos) e as falhas críticas de hardware/software (Glitches).

---

#### 💥 1. Ressonância Crítica (20 Natural)

Quando um Emissário atinge o ápice de sua sincronia, o dano não é apenas dobrado; ele é maximizado.

> [!DANGER] Protocolo de Letalidade
> 
> Em um **20 Natural**, você não rola os dados de dano base. Em vez disso:
> 
> 1. Assume o **valor máximo** de todos os dados da arma/técnica.
>     
> 2. Soma os modificadores de atributo.
>     
> 3. Rola **+1 dado extra** do mesmo tipo e soma ao total.
>     
> 
> **Fórmula:**
> 
> $$Dano_{Crítico} = (Max_{Dados} + Mod) + 1d_{Arma}$$

---

#### ⚠️ 2. Glitch de Sistema (1 Natural)

Um **1 Natural** representa uma falha crítica no fluxo de energia ou um travamento mecânico do equipamento tecnológico.

> [!BUG] Falha de Execução
> 
> No caso de um 1 Natural, o ataque falha automaticamente e gera um dos seguintes efeitos (conforme o tipo de arma):
> 
> - **Armas Tecnológicas:** Entram em _Loop de Dados_. O equipamento fica inoperante por $1d4$ rodadas (Exige uma Ação Menor de _Reboot_ e teste de Sincronia CD 15).
>     
> - **Técnicas Elementais:** Causam **Erosão Imediata**. O usuário recebe metade do dano da técnica em si mesmo e aumenta seu nível de **Corrupção** em +1.
>     
> - **Armas Brancas:** Perdem 1 ponto de **Integridade** (Desgaste).
>     

---

#### 🛡️ 3. Propriedade: Quebra de Blindagem

Algumas armas pesadas (como o Martelo Hidráulico ou Canhões de Pulso) possuem a tag **[Destrutiva]**. Elas são projetadas para moer o metal de Khaenri'ah.

> [!INFO] Destruição de RD
> 
> Sempre que um ataque com uma arma **Destrutiva** atinge um alvo com **Redução de Dano (RD)**:
> 
> - A RD do alvo é reduzida permanentemente em **-2 pontos** para aquele combate.
>     
> - Este efeito é cumulativo. Se a RD chegar a 0, o alvo torna-se **Vulnerável** (Dano Dobrado).
>     

---

#### 🏷️ 4. Classificação de Danos (Tags)

Para fins de resistências e imunidades, os danos são divididos em três categorias de processamento:

|**Categoria**|**Tipos**|**Notas de Sistema**|
|---|---|---|
|**Físico**|Impacto, Corte, Perfuração|Afetado normalmente por RD física.|
|**Elemental**|Pyro, Hydro, Electro, Cryo, Anemo, Geo, Dendro|Pode causar Reações [Ver 02_Elementos].|
|**Primordial**|**Lux** (Radiante), **Luna** (Abissal)|**Luna** ignora 50% da RD do alvo.|