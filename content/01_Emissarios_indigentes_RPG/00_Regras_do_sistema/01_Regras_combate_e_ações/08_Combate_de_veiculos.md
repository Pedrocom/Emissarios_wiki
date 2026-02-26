O combate mecanizado utiliza as mesmas bases do combate a pé, mas introduz modificadores de velocidade e riscos de colisão catastrófica.

---

### 1. Funções de Tripulação

Um veículo pode ter múltiplos ocupantes, cada um com uma função específica na economia de ações:

- **Piloto:** Realiza testes de **Agilidade** (manobra) ou **Sincronia** (sistemas). Sua Ação Padrão é usada para manobras complexas.
    
- **Artilheiro:** Utiliza armas acopladas ou armas próprias. Atacar de um veículo em movimento (acima de 12m/rodada) impõe **Desvantagem** automática em ataques de longa distância.
    
- **Engenheiro/Analista:** Usa ações para realizar reparos de emergência ou gerenciar as **Células de Fluxo (CF)** para evitar Glitches.
    

---

### 2. Movimentação e Manobras

Veículos possuem uma inércia que combatentes a pé não têm.

- **Velocidade de Cruzeiro:** Movimento normal sem gastar recursos extras.
    
- **Overdrive:** O piloto gasta **1 CF** para dobrar a velocidade por 1 rodada. Exige um teste de Agilidade (DT 15) para não perder o controle ao final do movimento.
    
- **Manobra de Esquiva:** O piloto usa sua **Reação** para somar o seu modificador de Agilidade à CA do veículo contra um único ataque.
    

---

### 3. Ataques e Defesa

- **Classe de Armadura (CA):** O veículo possui uma CA fixa baseada na sua estrutura.
    
- **Redução de Dano (RD):** Fundamental para veículos blindados. Veículos pesados ignoram pequenos calibres (danos abaixo de 5).
    
- **Alvejando Ocupantes:** Um atacante pode optar por atingir os passageiros em vez do veículo.
    
    - Veículos abertos (Motos, Buggies): Alvo possui **Meia Cobertura** (+2 CA).
        
    - Veículos fechados (Caminhonete, Blindado): Alvo possui **Coberura Total** (não pode ser atingido a menos que a blindagem seja perfurada).
        

---

### 4. Colisões e Atropelamentos

Quando um veículo atinge um alvo ou outro veículo, o dano é calculado pela massa e velocidade.

> [!DANGER] Cálculo de Impacto
> 
> O dano de colisão é baseado no deslocamento percorrido na rodada atual:
> 
> $$Dano = (\text{Metros percorridos} / 3) \times d6$$
> 
> _Exemplo: Um Blindado que percorreu 18 metros causa $6d6$ de dano de Impacto ao colidir._

- **Teste de Resistência:** O alvo atingido deve passar num teste de **Integridade (VIG)** ou será arremessado e ficará **Caído**.
    
- **Dano de Retrocesso:** O veículo que colide sofre metade do dano causado, ignorando sua própria RD (impacto interno).
    

---

### 5. Tabela de Falhas Críticas (Glitch de Veículo)

Sempre que o piloto rola um **1 Natural** ou o veículo cai a menos de 25% de PV, role 1d6:

|**Dado**|**Resultado**|**Consequência**|
|---|---|---|
|**1-2**|**Pane no Motor**|O veículo para imediatamente e consome 1 CF extra.|
|**3-4**|**Vazamento de Éter**|O veículo sofre 1d10 de dano Elemental (aleatório) por rodada.|
|**5**|**Perda de Direção**|O veículo se move em uma direção aleatória na velocidade máxima.|
|**6**|**Explosão de Módulo**|O veículo explode. Todos os ocupantes sofrem 4d10 de dano e o veículo é destruído.|

---

### 6. Logística de Reparo em Combate

O **Analista** pode tentar um reparo rápido:

- **Ação Padrão + 1 Sucata Tecnológica:** Recupera $1d10 + \text{Sincronia}$ de PV do veículo.
    
- Se o reparo for feito sob fogo pesado ou em alta velocidade, o teste tem **Desvantagem**.
    

### 🛹 6. Protocolo de Abordagem (Jumping & Boarding)

A abordagem ocorre quando um personagem tenta transferir sua massa de um veículo (origem) para outro (destino) em movimento.

#### A. O Salto (Ação de Movimento + Padrão)

Para realizar a abordagem, os veículos devem estar a uma distância máxima de **3 metros** entre si. O personagem gasta sua Ação de Movimento e deve passar num teste de **Agilidade (Acrobacia)**.

|**Condição de Velocidade**|**Dificuldade (DT)**|**Consequência da Falha**|
|---|---|---|
|**Velocidades Emparelhadas**|**DT 12**|O personagem se segura na borda (fica Pendurado).|
|**Velocidades Diferentes**|**DT 18**|**Queda Livre:** O personagem erra o salto.|
|**Manobras Evasivas** (Piloto inimigo usa Reação)|**DT +5**|O personagem é arremessado para longe.|

> [!DANGER] Penalidade de Velocidade
> 
> Se o salto for feito enquanto os veículos estão em **Overdrive**, o teste de Agilidade recebe **Desvantagem** automática devido à pressão do vento e instabilidade.

---

#### B. Consequências da Queda (Check de Integridade)

Se o personagem falhar no salto (Queda Livre), ele sofre dano de impacto baseado na velocidade do veículo de destino no momento da queda:

- **Dano de Queda:**
    
    $$(Metros / 3) \times d6$$
    
- **Status:** O personagem fica **Caído** e **Atordoado** por 1 rodada.
    
- **Logística:** O personagem é deixado para trás no mapa. O grupo precisará fazer uma manobra de resgate ou ele terá que se virar sozinho na zona de Anomalia.
    

---

#### C. Luta sobre o Chassi

Uma vez a bordo, o combate segue regras de **Instabilidade Tática**:

1. **Desvantagem em Ataques:** Qualquer ataque (corpo a corpo ou distância) feito enquanto se está em cima de um veículo em movimento tem **Desvantagem**, a menos que o personagem use uma Ação Menor para se "ancorar" (prendendo-se a cabos ou imãs).
    
2. **Teste de Equilíbrio:** Sempre que o Piloto realizar uma **Manobra de Esquiva** ou sofrer **Dano de Colisão**, todos em cima do veículo devem passar num teste de **Agilidade (DT 14)** ou caem do veículo imediatamente.
    

---

#### D. Manobras de Abordagem (Ações Específicas)

- **Sabotagem de Módulo:** O personagem tenta destruir uma peça vital (motor, Célula de Fluxo ou radar). Exige um teste de **Sincronia**. Em caso de sucesso, o veículo sofre um **Glitch** automático.
    
- **Extração de Piloto:** Tenta puxar o piloto para fora do assento. É um teste de **Atletismo (Potência)** resistido pela **Integridade** do Piloto. Se vencer, o piloto é arremessado para fora e o veículo fica descontrolado.
    
- **Ancoragem Magnética:** Se o personagem tiver um item de Modding magnético, ele ignora a Desvantagem de ataque enquanto estiver sobre o chassi de metal.