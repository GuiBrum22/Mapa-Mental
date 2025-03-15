# Mapa-Mental

```mermaid
graph LR;
    A["📌 Teorias Sociológicas Clássicas"] -->|1| B["📚 Durkheim - Fatos Sociais"] 
    B --> B1["📖 Definição: Regras e padrões coletivos que moldam o comportamento individual"] 
    B1 --> B2["🔗 Características: Exterioridade, Coercitividade, Generalidade"] 
    B2 --> B3["📝 Exemplo: O suicídio como fenômeno social e suas causas estruturais"] 

    A -->|2| C["🎯 Weber - Ação Social"] 
    C --> C1["📖 Definição: Ações individuais que têm significado e impacto na sociedade"] 
    C1 --> C2["🔍 Tipos: Racional com relação a fins, valores, afetiva, tradicional"] 
    C2 --> C3["📝 Exemplo: A escolha de uma profissão pode ser por paixão (afetiva) ou dinheiro (racional)"] 

    A -->|3| D["⚙️ Marx - Materialismo Histórico"] 
    D --> D1["📖 Definição: A economia determina a organização social e histórica"] 
    D1 --> D2["🔥 Luta de Classes: Conflito entre burguesia (donos do capital) e proletariado (trabalhadores)"] 
    D2 --> D3["📝 Exemplo: Revoluções e greves como resultado da exploração trabalhista"] 

    %% Estilizando os nós principais
    style A fill:#ffcc00,stroke:#333,stroke-width:3px
    style B fill:#ff6666,stroke:#990000,stroke-width:2px
    style C fill:#66ccff,stroke:#003366,stroke-width:2px
    style D fill:#99ff99,stroke:#006600,stroke-width:2px

    %% Estilizando os sub-nós
    classDef subnode fill:#ffffff,stroke:#888,stroke-width:1.5px,font-size:12px;
    class B1,B2,B3,C1,C2,C3,D1,D2,D3 subnode;
