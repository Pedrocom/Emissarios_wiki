
O cenário não é apenas um pano de fundo; ele é um agente ativo no combate. Operadores que ignoram o posicionamento no campo de batalha raramente sobrevivem ao primeiro encontro com Máquinas Amaldiçoadas.

---

### 🛡️ 1. Níveis de Cobertura

A cobertura fornece bônus à **CA (Classe de Armadura)** e a testes de resistência de **Agilidade** contra efeitos de área.

|**Tipo de Cobertura**|**Exemplo**|**Bônus (CA/AGI)**|
|---|---|---|
|**Meia Cobertura**|Muretas baixas, troncos finos, móveis.|**+2**|
|**Cobertura Superior**|Escombros altos, veículos, cantos de prédios.|**+5**|
|**Cobertura Total**|Atrás de paredes sólidas ou blindagem de _Bergs_.|**Alvo Intocável**|

> [!TIP] Lógica de Combate
> 
> Se um alvo está em **Cobertura Total**, ele não pode ser selecionado como alvo de ataques diretos ou técnicas que exijam linha de visão, a menos que a arma possua a propriedade de perfuração de superfícies.

---

### 🥾 2. Tipos de Terreno (Variáveis de Ambiente)

O terreno altera o custo de processamento do movimento. A fórmula básica de deslocamento é afetada pelo estado do solo:

$$Custo_{Movimento} = Metros \times Multiplicador$$

#### **A. Terreno Normal ($x1$)**

Estradas conservadas, interior de instalações de Khaenri'ah funcionais e planícies limpas.

#### **B. Terreno Difícil ($x2$)**

Entulho, neve profunda, lama de Sumeru ou áreas com destroços metálicos.

- **Efeito:** Cada metro percorrido custa o dobro. Atravessar 3 metros de entulho consome 6 metros do seu deslocamento total.
    

#### **C. Terreno Perigoso / Instável**

Após o silêncio dos Arcontes e a queda de Khaenri'ah, a natureza de Teyvat tornou-se hostil. Onde antes havia equilíbrio elemental, agora residem anomalias que desafiam a lógica e a integridade biológica/mecânica.

---

### 🔥 Pyro: Inferno Branco (Calor de Exaustão)

_Áreas: Natlan e zonas de bombardeamento antigo._

O oxigênio nestas áreas é consumido por uma combustão invisível e constante que ignora proteções térmicas comuns.

> [!DANGER] Mecânica de Sobrevivência
> 
> - **Teste de Exposição:** Exige um teste de **Integridade (VIG)** a cada 5 minutos.
>     
> - **Falha:** O personagem sofre **1 nível de Exaustão**.
>     
> - **Retrocesso:** Se o personagem usar qualquer técnica Pyro aqui, sofre $1d8$ de dano de fogo por retrocesso de calor.
>     

---

### 💧 Hydro: Chuva Ácida de Sukhur

_Áreas: Deserto e zonas de hidro-corrosão._

Uma precipitação constante de água quimicamente instável que dissolve ligas metálicas e tecidos orgânicos.

> [!FAILURE] Mecânica de Corrosão
> 
> - **Efeito:** A cada hora de exposição direta, reduz a **CA (Defesa)** de armaduras e a durabilidade de armas em **-5 pontos**.
>     
> - **Reparo:** Exige um teste de Manutenção Tecnológica e uso de sucata para restaurar os equipamentos ao estado original.
>     

---

### ⚡ Electro: Tempestades de Raio (Ponto Zero)

_Áreas: Inazuma e arredores das ruínas de Baal._

Após a morte da Arconte Electro, a energia nas ruínas tornou-se errática, buscando aterramento em qualquer condutor.

> [!DANGER] Mecânica de Combate
> 
> - **Frequência:** A cada 3 rodadas de combate.
>     
> - **Teste:** Todos os operadores devem passar em um teste de **Agilidade (DEX)**.
>     
> - **Falha:** Atingido por um raio que causa **$2d10$ de dano Electro** e aplica a Aura Elemental.
>     

---

### ❄️ Cryo: Zero Absoluto (Fragilidade Térmica)

_Áreas: Dragonspine e estepes de Snezhnaya._

O frio é tão intenso que as moléculas de metal e os fluidos biológicos atingem o ponto de cristalização instantânea.

> [!INFO] Mecânica de Estase
> 
> - **Mobilidade:** O movimento é reduzido à metade e testes de **Agilidade** têm **Desvantagem**.
>     
> - **Vulnerabilidade:** Qualquer dano físico de **Impacto** recebido aqui é **dobrado**, pois o corpo e o equipamento tornam-se quebradiços como vidro.
>     

---

### 🌪️ Anemo: Ventos Cortantes de Hadramaveth

_Áreas: Deserto profundo e fendas de alta pressão._

Anomalias atmosféricas que carregam fragmentos de tecnologia antiga a velocidades supersônicas.

> [!WARNING] Mecânica de Posicionamento
> 
> - **Deslocamento:** Exige um teste de **Proeza de Titã (FOR)** para se mover contra o vento.
>     
> - **Falha:** O personagem é empurrado $1d6$ metros na direção do vento e sofre $1d10$ de dano de corte pelos destroços metálicos.
>     

---

### 🪨 Geo: Tremores de Petrificação

_Áreas: Minas de Liyue e fendas tectônicas._

Vibrações de baixa frequência que forçam a calcificação acelerada de tecidos orgânicos e circuitos.

> [!CAUTION] Mecânica de Imobilização
> 
> - **Teste de Entrada:** Teste de **Integridade (VIG)** ao entrar na área.
>     
> - **Falha:** O personagem fica **Imobilizado**.
>     
> - **Petrificação:** A cada turno imobilizado, o alvo perde $1d4$ PV. O estado só é revertido com um choque de energia Hydro ou força bruta externa.
>     

---

### 🌿 Dendro: Florestas Vivas (Ar Mortal)

_Áreas: Interior de Sumeru._

Zonas onde a vegetação exala esporos que se infiltram em filtros de ar e pulmões, agindo como um agente corrosivo.

> [!WARNING] Mecânica de Mácula
> 
> - **Teste:** Teste de **Integridade (VIG)** a cada minuto de exposição.
>     
> - **Falha:** O personagem acumula **+1 ponto de Corrupção** e sofre dano contínuo de veneno ($1d6$ por turno) até ser descontaminado.
>     

---

### ☀️ Lux: Tempestade Solar (Radiação Divina)

_Áreas: Céu aberto sob influência direta de Celestia._

Radiação solar pura e sem filtros, calcinando tudo o que toca.

> [!DANGER] Mecânica de Exposição
> 
> - **Combate:** 1 turno exposto diretamente ao sol causa **$1d16$ de dano de Lux**.
>     
> - **Viagem:** A cada 10 minutos de deslocamento, o grupo sofre **$1d10$ de dano**.
>     
> - _Estratégia:_ Exige movimento noturno ou uso de coberturas pesadas.
>     

---

### 🌑 Luna: Mar de Sombras (Erosão de Identidade)

_Áreas: Profundezas de Khaenri'ah e zonas de colapso abissal._

Locais onde o tempo é distorcido e a realidade é substituída pelo nada.

> [!ABSTRACT] Mecânica de Vazio
> 
> - **Teste Mental:** A cada rodada, teste de **Sincronia (INT)**.
>     
> - **Falha:** O personagem sofre alucinações táticas (**Desvantagem** em testes de Instinto/Iniciativa) e ganha **+1 de Corrupção**.
>     
> - **Dano:** Qualquer dano de Luna recebido aqui **ignora 100% da RD (Redução de Dano)**.
>
---

### 🌫️ 3. Visibilidade e Ocultamento

Essencial para mecânicas de Stealth (Furtividade) e ataques à distância via rádio.

- **Penumbra (Luz Fraca):** Desvantagem em testes de Percepção baseados na visão.
    
- **Escuridão Total / Névoa Abissal:** Criaturas são consideradas em **Cobertura Total** visual. Ataques contra alvos que você não vê têm Desvantagem extrema.
    

> [!WARNING] Sensores Tecnológicos
> 
> Máquinas e Emissários equipados com visores térmicos ou sensores de pulso ignoram penalidades de Penumbra e Névoa, mas podem ser "cegados" por granadas de pulso eletromagnético (EMP).