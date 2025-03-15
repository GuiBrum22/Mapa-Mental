# Mapa-Mental

```mermaid
graph LR;
    A["📌 Teorias Sociológicas Clássicas"] -->|1| B["📚 Durkheim - Fatos Sociais"] 
    B --> B1["📖 Definição: Regras coletivas que moldam o comportamento individual"] 
    B1 --> B2["🔗 Características"] 
    B2 --> B3["🔹 Exterioridade: Independem do indivíduo"] 
    B2 --> B4["🔹 Coercitividade: Impõem-se sobre as pessoas"] 
    B2 --> B5["🔹 Generalidade: São comuns a um grupo"] 
    B --> B6["📝 Exemplos"] 
    B6 --> B7["📊 O suicídio como fenômeno social"] 
    B6 --> B8["🏫 A escola como forma de transmissão de normas sociais"] 

    A -->|2| C["🎯 Weber - Ação Social"] 
    C --> C1["📖 Definição: Atos individuais influenciados pelo sentido subjetivo"] 
    C1 --> C2["🔍 Tipos de Ação Social"] 
    C2 --> C3["🔹 Racional com relação a fins"]
    C3 --> C4["📌 Exemplo: Um empresário visando lucro"]
    C2 --> C5["🔹 Racional com relação a valores"]
    C5 --> C6["📌 Exemplo: Um ativista ambiental"]
    C2 --> C7["🔹 Afetiva"]
    C7 --> C8["📌 Exemplo: Tomar uma decisão por amor ou raiva"]
    C2 --> C9["🔹 Tradicional"]
    C9 --> C10["📌 Exemplo: Seguir rituais religiosos"]
    C --> C11["📝 Exemplos"] 
    C11 --> C12["📊 O mercado de trabalho e a ética protestante"] 
    C11 --> C13["🏛️ A burocracia como forma de organização eficiente"] 

    A -->|3| D["⚙️ Marx - Materialismo Histórico"] 
    D --> D1["📖 Definição: A economia molda a organização social e histórica"] 
    D1 --> D2["🔥 Luta de Classes"] 
    D2 --> D3["⚔️ Burguesia: Donos dos meios de produção"] 
    D2 --> D4["⚔️ Proletariado: Trabalhadores explorados"] 
    D2 --> D5["⚠️ Consequências: Exploração, desigualdade e revoluções"] 
    D --> D6["📌 Superestrutura e Infraestrutura"] 
    D6 --> D7["🏛️ Superestrutura: Cultura, leis, política"]
    D7 --> D8["📌 Controladas pela classe dominante"]
    D6 --> D9["🏭 Infraestrutura: Economia e relações de produção"]
    D --> D10["📝 Exemplos"] 
    D10 --> D11["⚙️ O capitalismo e a alienação do trabalhador"] 
    D10 --> D12["🏗️ Movimentos revolucionários na história"] 

    %% Estilizando os nós principais
    style A fill:#ffcc00,stroke:#333,stroke-width:3px;
    style B fill:#ff6666,stroke:#990000,stroke-width:2px;
    style C fill:#66ccff,stroke:#003366,stroke-width:2px;
    style D fill:#99ff99,stroke:#006600,stroke-width:2px;

    %% Estilizando os sub-nós (Definição, Características, Exemplos)
    classDef subnode fill:#ffffff,stroke:#888,stroke-width:1.5px,font-size:12px;
    class B1,B2,B3,B4,B5,B6,B7,B8,
          C1,C2,C3,C4,C5,C6,C7,C8,C9,C10,C11,C12,C13,
          D1,D2,D3,D4,D5,D6,D7,D8,D9,D10,D11,D12 subnode;
