# Sprint 0 – Onboarding Kdenlive

A Sprint 0 é a etapa de onboarding do projeto. Para participar, é necessário primeiro criar uma conta no KDE Identity, o que permite acessar o repositório do Kdenlive no GitLab.

Após isso, cada aluno deve criar um fork do repositório oficial, permitindo realizar alterações de forma independente antes de submeter contribuições ao projeto principal.

---

# Sobre o Kdenlive

O Kdenlive é um editor de vídeo gratuito e open source, voltado tanto para usuários iniciantes quanto para edições mais avançadas e profissionais. Ele permite a criação e edição de vídeos por meio de uma linha do tempo, onde clipes de vídeo, áudio, imagens e efeitos são organizados para compor o projeto final.

O projeto é desenvolvido principalmente em C++ e utiliza o MLT Framework como motor central de processamento multimídia. O MLT é responsável por tarefas como decodificação de áudio e vídeo, aplicação de efeitos, transições e renderização final do projeto.

Além disso, o Kdenlive utiliza diversas bibliotecas externas para expandir suas funcionalidades, como:

- **frei0r**: efeitos visuais de vídeo  
- **LADSPA**: efeitos de áudio  
- Outras bibliotecas para processamento de mídia, sincronização e manipulação de formatos  

---

# Arquitetura do sistema

A arquitetura do Kdenlive segue uma separação clara entre interface e processamento:

- **Interface gráfica (Qt + KDE Frameworks)**  
  Responsável pela interação do usuário, incluindo timeline, menus, botões e ferramentas de edição.

- **Motor de processamento (MLT Framework)**  
  Responsável pela execução das operações de edição, efeitos e renderização.

Essa separação torna o sistema mais modular e facilita a manutenção e evolução do projeto.

---

# Desenvolvimento e contribuição

O projeto é altamente modular e segue padrões de grandes projetos open source. O desenvolvimento acontece principalmente no **KDE Invent**, utilizando um fluxo baseado em Git com:

- Issues
- Branches
- Merge Requests

Além de código, o projeto também aceita contribuições como documentação, tradução, testes e report de bugs.

---

# Como contribuir

Para contribuir com o Kdenlive, deve-se:

1. Escolher uma issue no GitLab  
2. Criar uma branch separada para realizar as alterações  
3. Implementar a mudança no código  
4. Enviar um Merge Request para revisão  

A comunidade então revisa o código, sugere ajustes quando necessário e discute melhorias. Se tudo estiver correto, a contribuição é aprovada e integrada ao projeto principal.
