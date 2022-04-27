# Fontes: 
    • https://www.youtube.com/watch?v=34RvRBXzvMo&list=PLxI8Can9yAHdAU8zIvJTKcbhgRyzwjII2&index=2
    • https://drive.google.com/file/d/18knJ86Eb1sCwkFYWcc2boTR24eeCFESI/view?usp=sharing

# Aula 1 - Introdução

## 1. Definição
    • Sistema no qual componentes de hardware e/ou software, localizados em computadores interligados
    em rede, comunicam-se e coordenam ações (processos e/ou Threads) apenas enviando mensagens entre si.
    
## 2. Objetivo Principal:
    • Link entre usuários e recursos
         • Compartilhamento de recursos (Arquivos, Banco de dados, Impressora, Discos)
         • Segurança desees recursos
         • Redução da comunicação indesejada
    
    • Transparência (Fazer o usuário pensar que o sistema é único - Uma só entidade - Um sistema geral)
    
    • Flexibilidade (Adicionar ou remover recursos sem o usuário perceber)
    
    • Escalabilidade (Propriedade que mede a capacidade do sistema em lidar facilmente com uma quantidade 
    crescente de trabalho ou processos)
         •  Escalabilidade de tamanho (Número de processos / usuários)
         •  Escalabilidade Geográfica (Distãncia máxima entre os nós)
         •  Escalabilidade Administrativa (Número de domínios administrativos)
    
## 3. Desafios a serem combatidos:
    • Concorrência (Trabalho paralelo usando os mesmos recursos)
    • Inexistência de relógio global (Sincronização entre computadores e mensagens coordenando suas tarefas)
    • Falhas independentes (Isolamento dos computadores da rede para não causar panes generalizadas)
    • Heterogeneidade
    • Sistemas abertos
    • Segurança
    • Tratamento de falhas
    • Qualidade de serviço
    
## 4. Exemplos de Sistemas Distribuidos:
    • Pesquisas na Web (Protocolo HTTP)
    • Massively Multiplayer Online games (MMOGs)
    
## 5. Conceitos Importantes:

### 5.1. Middleware (Camada do meio):
    • Camada que fica situado entre a aplicação e o sistema operacional e visa a projeção de informações entre maquinas 
    que podem possuir heterogeneidades (Papel de corretor / Comunicação Proprietario - Inquilino);
    
    • Aplicação > Interface padrão (Stardart API) > Middleware > Specific API > Operating System > Comunication System
    
    • Representado por softwares que conectam programas separados e já existentes;
    • Objetivo: Tirar a complexidade das camadas inferiores 

### 5.2. Sistemas Distribuídos(SD) Vs Computação Paralela(CP):
    • CP - Fortemente acoplados e comunicação mais frequente - Ex.: Compartilhamento de recurso (Mesma memória)
    • SD - Fracamente acoplados e comunicação menos frequente - Ex.: Compartilhamento de conteudo (Memórias individuais comunicando-se entre si)
