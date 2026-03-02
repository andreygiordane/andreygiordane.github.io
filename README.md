# Portfólio Web Interativo | Andrey Giordane

Um portfólio web moderno, responsivo e imersivo, desenvolvido para apresentar projetos, competências e trajetória profissional de forma interativa. O principal diferencial deste projeto é a integração em tempo real com a API do GitHub e a implementação de um Terminal Interativo funcional diretamente no navegador.

![projeto](https://github.com/user-attachments/assets/6aebf424-a889-4179-9cf0-edf59641573d)


# Principais Funcionalidades

Terminal Interativo: Um emulador de consola onde os visitantes podem introduzir comandos reais (como help, about, skills, projects) para navegar pelas informações do perfil.

Integração com a API do GitHub: A secção de projetos consome a API pública do GitHub em tempo real para procurar e apresentar automaticamente os repositórios mais recentes e as respetivas linguagens.

Totalmente Responsivo: Navegação e layout adaptados para dispositivos móveis, incluindo um menu de navegação retrátil e uma grelha fluida.

Design Moderno (Glassmorphism): Interface baseada em "Dark Mode" (modo escuro) com elementos translúcidos, efeito de vidro e animações de fundo subtis.

Modal de Projetos: Sistema de janelas modais (pop-ups) que exibe informações detalhadas sobre a criação, tecnologias aplicadas e links diretos para cada repositório.

Efeito Typewriter: Animação de texto simulando uma máquina de escrever na secção inicial para destacar o foco e a área de estudo.

# Tecnologias e Ferramentas Utilizadas

O desenvolvimento deste projeto recorreu às seguintes tecnologias e bibliotecas:

# Frontend

• HTML5: Estruturação semântica da aplicação.

• Tailwind CSS: Framework de CSS utilitário (via CDN) para estilização ágil, gestão de tipografia e design responsivo.

• JavaScript (Vanilla): Lógica de programação para o funcionamento do terminal, consumo de dados externos, animações de scroll e manipulação do DOM, sem dependência de frameworks complexos.

# APIs e Integrações

• GitHub REST API: Utilizada através do método fetch() para obter dinamicamente os dados dos repositórios públicos.

# Design e Elementos Visuais

• FontAwesome 6: Biblioteca para a iconografia da interface de utilizador.

• Devicon: Biblioteca específica para os logótipos das linguagens de programação e ferramentas de desenvolvimento (Java, JS, PostgreSQL, etc.).

• Google Fonts: Utilização das famílias tipográficas Inter (para os blocos de texto) e Fira Code (para a estética de código no emulador de terminal).

# Como Executar o Projeto Localmente

Sendo um projeto construído com tecnologias web nativas (HTML, CSS e JS puros), não requer processos de build ou compilação complexos.

# Alojamento e Deploy

O projeto está otimizado para ser alojado em serviços de hosting estático. Recomenda-se a utilização das seguintes plataformas gratuitas:

GitHub Pages
