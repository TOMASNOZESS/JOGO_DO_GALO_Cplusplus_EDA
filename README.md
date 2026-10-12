# ❌ Jogo do Galo (EDA — C++)

Projeto académico desenvolvido em **C++** no âmbito da unidade curricular de **Estruturas de Dados e Algoritmos (EDA)**, apresentando uma versão interativa e estruturada do clássico Jogo do Galo (*Tic-Tac-Toe*). O projeto combina gestão dinâmica de jogadores, múltiplos modos de jogo, níveis de dificuldade ajustáveis para Inteligência Artificial e persistência de dados em ficheiro.

---

## 🚀 Funcionalidades Principais

- **Gestão de Perfil de Jogadores:**
  - Adição, listagem e remoção de perfis de jogadores.
  - Gravação e carregamento automático das pontuações (*scores*) a partir do ficheiro local `filejogodogalo.txt`.
- **Modos de Jogo:**
  - **1. Jogador vs Computador:** Desafia a Inteligência Artificial.
  - **2. Jogador vs Jogador:** Partidas locais entre dois jogadores.
  - **3. Computador vs Computador:** Modo de simulação entre duas instâncias de IA.
- **Níveis de Dificuldade da IA:**
  - **Elementar:** Jogadas aleatórias simples.
  - **Básico:** Validação de jogadas básicas.
  - **Médio:** Análise defensiva e ofensiva de padrões de vitória.
  - **Avançado:** Tomada de decisão otimizada para bloquear e vencer.
- **Tabela de Classificação (*Top 10*):** Visualização do *placar* com as melhores pontuações dos jogadores registados.
- **Interface Consola Dinâmica:** Apresentação visual limpa na consola com suporte a sequências de cores ANSI para destacar as marcas dos jogadores (`X` e `O`).

---

## 🛠️ Tecnologias & Conceitos Utilizados

- **Linguagem:** C++ (Padrão C++11 ou superior).
- **Estruturas de Dados:** Manipulação de vetores/arrays de objetos (`struct Jogador`), cadeias de caracteres (`std::string`), e streams de ficheiros (`std::ifstream`, `std::ofstream`).
- **Persistência de Dados:** Leitura e escrita formatada para manutenção de estado e histórico de classificações.

---

## 🎮 Como Compilar e Executar

1. Clona este repositório para o teu computador:
   ```bash
   git clone [https://github.com/TOMASNOZESS/JOGO_DO_GALO_C++_EDA.git](https://github.com/TOMASNOZESS/JOGO_DO_GALO_C++_EDA.git)
