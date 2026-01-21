# 🩺 GX Agendamentos | Gestão Inteligente para Clínicas
<img width="1891" height="903" alt="image" src="https://github.com/user-attachments/assets/97b29d95-9121-4d09-9b05-29a22f0a3745" />
Uma landing page moderna, elegante e de alta conversão desenvolvida para a GX Agendamentos. O projeto foca em soluções de gestão para clínicas de fisioterapia e massoterapia, apresentando funcionalidades como prontuários digitais, agendamento online e controle financeiro através de uma interface intuitiva.

# 🚀 Funcionalidades
Alternância de Tema (Dark/Light Mode): Suporte nativo a temas claro e escuro, com salvamento automático da preferência do usuário via localStorage.

Animações de Entrada (Scroll Reveal): Elementos da página surgem suavemente conforme o usuário navega, utilizando a API Intersection Observer para melhor performance.

Botão Voltar ao Topo: Interface inteligente que aparece após 300px de rolagem, permitindo um retorno fluido ao início da página.

Integração com WhatsApp: Botões de ação (CTAs) configurados para direcionar o cliente diretamente para o atendimento, aumentando a taxa de conversão.

Cards de Preços Dinâmicos: Exibição estratégica de planos (Semestral e Anual) com destaque visual para a opção mais vantajosa.

Design Responsivo: Layout totalmente adaptável para dispositivos móveis, tablets e desktops utilizando CSS Grid e Flexbox.

# 🛠️ Tecnologias Utilizadas
O projeto foi construído utilizando as tecnologias fundamentais do desenvolvimento Web:

HTML5: Estruturação semântica avançada, otimizada para SEO e acessibilidade.

CSS3: Estilização moderna com variáveis customizadas, efeitos de transparência (Glassmorphism) e animações complexas.

JavaScript: Lógica para manipulação do DOM, controle de temas e monitoramento de eventos de scroll.

# 📂 Estrutura de Arquivos
<img width="668" height="226" alt="image" src="https://github.com/user-attachments/assets/974b5346-6406-40a7-b55e-77f628871a4d" />

# 📝 Como funciona o código?
A inteligência da página está dividida em três frentes principais:

Gestão de Tema: O JavaScript verifica se o usuário já aplicou o tema escuro anteriormente para manter a consistência visual. Ao clicar no botão, as variáveis CSS são atualizadas em tempo real.

Sistema de Animação: Utiliza o Intersection Observer para aplicar classes de visibilidade apenas quando os elementos (como cards de planos) entram no campo de visão, economizando recursos.

Comportamento de Scroll: O evento window.addEventListener('scroll') monitora a posição da página para exibir o botão de retorno e gerenciar a suavidade do movimento.

# 🚀 Como Executar o Projeto
Para visualizar o projeto localmente:

Clone este repositório(git clone https://github.com/marcosmerencio/landing-page-gx-agendamentos.git) ou baixe os arquivos.

Certifique-se de manter a pasta assets, css e js no mesmo diretório do index.html.

Abra o arquivo index.html em qualquer navegador moderno.

# 📌 Boas Práticas Aplicadas
Separação de Responsabilidades: Divisão clara entre estrutura, estilo e comportamento.

SEO & Social: Inclusão de Meta Tags e Open Graph para compartilhamento otimizado em redes sociais.

UX Focus: Implementação de estados de hover e transições suaves para evitar quebras visuais bruscas.

# ✒️ Autor
Marcos Merencio / Desenvolvedor Web (em formação)

📄 Licença
Este projeto é livre para fins de estudo e portfólio.
