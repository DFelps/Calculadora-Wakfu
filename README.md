# 🧮 Calculadora Wakfu --- Simulator de Dano + Inventário Real

Bem-vindo à **Calculadora Wakfu**, uma ferramenta feita para ajudar
jogadores a criar, testar e comparar builds usando:

-   📌 **Itens reais extraídos do gamedata**
-   📌 **Cálculo de dano baseado na fórmula oficial**
-   📌 **Simulação em tempo real diretamente no navegador**

Este projeto é totalmente open-source e roda direto no GitHub Pages.

------------------------------------------------------------------------

## 🔧 Status do Projeto --- *Em Desenvolvimento*

Este projeto ainda está em **desenvolvimento ativo**.\
Diversas funcionalidades estão sendo adicionadas ou aprimoradas,
incluindo:

-   Aperfeiçoamento dos cálculos de dano\
-   Criação de interface para seleção de itens\
-   Sistema de inventário completo usando dados reais do jogo\
-   Otimização do carregamento dos arquivos JSON\
-   Melhorias visuais e responsividade\

Por ser um projeto em construção, algumas partes ainda podem:

-   Estar incompletas\
-   Receber ajustes futuros\
-   Sofrer mudanças estruturais\
-   Conter dados em versão parcial ou não final\
-   Ser redesenhadas para melhorar desempenho ou usabilidade

------------------------------------------------------------------------

## 🌐 Acesse agora

### 🔗 **Calculadora completa**

👉 https://dfelps.github.io/Calculadora-Wakfu/wakfu-calculadora.html

### 📦 Exemplos de banco de dados de equipamentos

Todos os itens foram extraídos automaticamente do gamedata do Wakfu
(equipamentos reais do jogo), classificados por categoria.

**Exemplo --- Armas secundárias → Adagas:**\
👉
https://dfelps.github.io/Calculadora-Wakfu/equip_categories/adaga\_\_mao_secundaria.json

Outras categorias incluem: - capacete\
- amuleto\
- anel\
- capa\
- botas\
- ombreiras\
- cinto\
- peitoral\
- armas 1 mão\
- armas 2 mãos\
- mão secundária (escudo, adaga, tocha...)\
- mascotes\
- montarias\
- emblemas\
- ferramentas

Cada arquivo JSON possui somente: - `id` - `name` - `description` -
`level` - `rarity` - `slot` - `effects` (apenas em PT-BR, limpo e
filtrado)

------------------------------------------------------------------------

## 🧰 Sobre o inventário de itens (equip_categories)

Os itens são extraídos diretamente do gamedata da Ankama, filtrados,
limpos e organizados usando scripts Python.

Os JSONs foram processados para conter somente: - Nome em PT-BR\
- Descrição em PT-BR\
- Nível\
- Raridade\
- Slot (categoria do equipamento)\
- Efeitos traduzidos e limpos\
- Um arquivo para cada categoria

Esses arquivos permitem que a calculadora: - Crie **inventários
reais** - Permita calcular builds usando **itens verdadeiros do jogo** -
Mostre previsões de dano baseadas em combinações reais

------------------------------------------------------------------------

## 🧮 Como funciona a calculadora de dano?

A calculadora usa: - Seus atributos escolhidos - As masterias (geral,
corpo-a-corpo, distância, etc.) - Backstab, crítico, danos
indiretos e outros modificadores

Ela então aplica a fórmula de dano do Wakfu para estimar **dano final**,
variando entre: - Golpe comum\
- Golpe crítico\
- Backstab crítico\
- Buffs e debuffs (se aplicável)

------------------------------------------------------------------------

## 📜 Licença

Este projeto é open-source.\
Os dados do jogo Wakfu pertencem à Ankama.\
Esta ferramenta é um projeto da comunidade, sem fins lucrativos.

------------------------------------------------------------------------

## ⭐ Créditos

-   Dados fornecidos pela comunidade Wakfu\
-   Inspiração em builders e calculadoras clássicas

------------------------------------------------------------------------
