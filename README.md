# Mapa-Mental

```mermaid
graph LR;
    A["📌 Teorias Sociológicas Clássicas"] -->|1| B["📚 Durkheim - Fatos Sociais"] 
    B --> B1["📖 Definição: Regras coletivas que moldam o comportamento individual"] 
    B1 --> B2["🔗 Características"] 
    B2 --> B2a["🔹 Exterioridade: Independem do indivíduo"] 
    B2 --> B2b["🔹 Coercitividade: Impõem-se sobre as pessoas"] 
    B2 --> B2c["🔹 Generalidade: São comuns a um grupo"] 
    B --> B3["📝 Exemplos"] 
    B3 --> B3a["📊 O suicídio como fenômeno social"] 
    B3 --> B3b["🏫 A escola como forma de transmissão de normas sociais"] 

    A -->|2| C["🎯 Weber - Ação Social"] 
    C --> C1["📖 Definição: Atos individuais influenciados pelo sentido subjetivo"] 
    C1 --> C2["🔍 Tipos de Ação Social"] 
    C2 --> C2a["🔹 Racional com relação a fins"]
    C2a --> C2a1["📌 Exemplo: Um empresário visando lucro"]
    C2 --> C2b["🔹 Racional com relação a valores"]
    C2b --> C2b1["📌 Exemplo: Um ativista ambiental"]
    C2 --> C2c["🔹 Afetiva"]
    C2c --> C2c1["📌 Exemplo: Tomar uma decisão por amor ou raiva"]
    C2 --> C2d["🔹 Tradicional"]
    C2d --> C2d1["📌 Exemplo: Seguir rituais religiosos"]
    C --> C3["📝 Exemplos"] 
    C3 --> C3a["📊 O mercado de trabalho e a ética protestante"] 
    C3 --> C3b["🏛️ A burocracia como forma de organização eficiente"] 

    A -->|3| D["⚙️ Marx - Materialismo Histórico"] 
    D --> D1["📖 Definição: A economia molda a organização social e histórica"] 
    D1 --> D2["🔥 Luta de Classes"] 
    D2 --> D2a["⚔️ Burguesia: Donos dos meios de produção"] 
    D2 --> D2b["⚔️ Proletariado: Trabalhadores explorados"] 
    D2 --> D2c["⚠️ Consequências: Exploração, desigualdade e revoluções"] 
    D --> D3["📌 Superestrutura e Infraestrutura"] 
    D3 --> D3a["🏛️ Superestrutura: Cultura, leis, política"]
    D3a --> D3a1["📌 Controladas pela classe dominante"]
    D3 --> D3b["🏭 Infraestrutura: Economia e relações de produção"]
    D --> D4["📝 Exemplos"] 
    D4 --> D4a["⚙️ O capitalismo e a alienação do trabalhador"] 
    D4 --> D4b["🏗️ Movimentos revolucionários na história"] 

    %% Estilizando os nós principais
    classDef main fill:#ffcc00,stroke:#333,stroke-width:3px;
    classDef theory fill:#ff6666,stroke:#990000,stroke-width:2px;
    classDef action fill:#66ccff,stroke:#003366,stroke-width:2px;
    classDef marx fill:#99ff99,stroke:#006600,stroke-width:2px;

    %% Estilizando os sub-nós
    classDef subnode fill:#ffffff,stroke:#888,stroke-width:1.5px,font-size:12px;
    class A main;
    class B theory;
    class C action;
    class D marx;
    class B1,B2,B2a,B2b,B2c,B3,B3a,B3b,
          C1,C2,C2a,C2a1,C2b,C2b1,C2c,C2c1,C2d,C2d1,C3,C3a,C3b,
          D1,D2,D2a,D2b,D2c,D3,D3a,D3a1,D3b,D4,D4a,D4b subnode;
