 🗳
Participa DF - Ouvidoria Digital
Sistema de ouvidoria acessível, multicanal e segura. Desenvolvido para o Hackathon com foco em cidadania e inclusão.
Sobre o Projeto
O Participa DF é uma aplicação web moderna que permite aos cidadãos registrarem manifestações (sugestões, críticas, elogios, denúncias) de forma inclusiva.
Diferenciais:
🗣
Multicanalidade: Suporte para envio de relatos por Áudio, Vídeo e Imagem.
♿
Acessibilidade Total: Controles de alto contraste, tamanho de fonte e modo escuro. Navegação otimizada por teclado (WCAG 2.1 AA).
🔒
Anonimato: Opção de envio seguro sem identificação. 📱
PWA: Instalação como aplicativo em qualquer dispositivo.
🛠
Tecnologias Utilizadas
Frontend: Next.js 15 (App Router) Estilização: Tailwind CSS Backend/Storage: Supabase Ícones: Lucide React
Utils: date-fns, qrcode.react
📂
Estrutura do Projeto
Como Rodar o Projeto
1. Instale as dependências:
npm install
2. Configure as variáveis de ambiente:
Crie um arquivo .env.local na raiz com suas credenciais do Supabase: NEXT_PUBLIC_SUPABASE_URL=sua_url NEXT_PUBLIC_SUPABASE_ANON_KEY=sua_chave
3. Inicie o servidor de desenvolvimento:
npm run dev
4. Acesse:
http://localhost:3000
🏗
Decisões Técnicas
Next.js App Router: Escolhido pela performance, SEO e facilidade de roteamento. Tailwind CSS: Para desenvolvimento rápido de uma interface responsiva e customizável.
Supabase: Backend-as-a-Service para persistência de dados e armazenamento de arquivos (blobs) com baixa latência.
Micro-interações: Uso de animações sutis e feedback visual para melhorar a experiência do usuário (UX).
♿
Acessibilidade
O projeto segue estritamente as diretrizes WCAG 2.1 AA: Uso correto de tags semânticas HTML5.
Atributos aria-label em botões e inputs.
Contraste de cores validado.
Foco visível para navegação por teclado.
🎯
Funcionalidades Principais
1. Registro de Manifestações: Interface intuitiva para envio de sugestões, elogios, reclamações e denúncias.
2. Gravação de Áudio: Permite que o cidadão grave sua manifestação por voz diretamente no navegador.
3. Upload de Arquivos: Suporte para envio de imagens e vídeos como evidências ou complementos.
4. Protocolo de Acompanhamento: Geração automática de protocolo único com QR Code para rastreamento.
5. Controles de Acessibilidade: Ajustes de fonte, contraste e tema personalizáveis pelo usuário.
6. Modo Offline (PWA): Funciona mesmo sem conexão à internet, sincronizando dados posteriormente.
Arquitetura do Sistema
Frontend (Next.js)
Renderização Server-Side (SSR) para melhor SEO Componentes reutilizáveis e modulares Gerenciamento de estado com React Hooks
Backend (Supabase)
Banco de dados PostgreSQL gerenciado Storage para arquivos de mídia
APIs REST automáticas
Segurança com Row Level Security (RLS)
🔐
Segurança e Privacidade
Anonimato garantido: Opção de envio sem identificação pessoal Criptografia: Dados transmitidos via HTTPS
Armazenamento seguro: Arquivos hospedados em infraestrutura confiável LGPD compliant: Respeito às normas de proteção de dados
🎥
Demonstração
Link do vídeo demonstrativo: [A ser adicionado]
O vídeo apresenta todas as funcionalidades do sistema, com foco na experiência do usuário e nos recursos de acessibilidade.
👥
Autor
Nome: César Augusto
CNPJ: 59.171.452/0001-89
Projeto: Desenvolvido para o Hackathon Participa DF
📝
Licença e Uso
Este projeto foi desenvolvido como parte do Hackathon Participa DF, com foco em inovação cívica e inclusão digital.
Participa DF - Ouvidoria Digital
  🚀
          ouvidoria-participa-df/
├── app/
│ ├── page.js
│   ├── manifestacao/
# Next.js App Router
# Home Page
# Página de envio
# Página de confirmação
# Componentes React
│   └── protocolo/
├── components/
│   ├── FormManifestacao  # Formulário principal
│   ├── GravadorAudio     # Widget de gravação
│   ├── UploadArquivos    # Widget de upload
│   └── BotaoAcessibilidade # Controle A11y
├── lib/
│   └── supabase.js
└── public/
# Utilitários
# Cliente Supabase
# Assets estáticos
 ⚡
           📊
          Tecnologia a serviço da cidadania
