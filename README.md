# 🐂 BUBATAG SITE

### Conectando tradição e inovação no monitoramento inteligente de bubalinos.

O **BUBATAG Site** é o projeto responsável pela apresentação institucional do BUBATAG, uma solução tecnológica voltada ao monitoramento inteligente de rebanhos bubalinos.

A plataforma apresenta a proposta do projeto, os desafios enfrentados pelos produtores e como a integração entre **Internet das Coisas (IoT), software e tecnologia** pode contribuir para um manejo mais seguro, eficiente e sustentável.

🌐 **Acesse o site:** [bubatag-site.vercel.app](https://bubatag-site.vercel.app/)

---

## 📌 Sobre o projeto

O site foi desenvolvido para apresentar o BUBATAG ao público, demonstrando sua proposta, seus objetivos e os benefícios que a tecnologia pode proporcionar à bubalinocultura.

O projeto BUBATAG busca desenvolver um sistema de monitoramento que integra dispositivos inteligentes e aplicações digitais para acompanhar informações importantes dos animais, auxiliando os produtores na tomada de decisões.

### Objetivos do site

- Apresentar o projeto BUBATAG e sua proposta tecnológica.
- Contextualizar os principais desafios da criação de búfalos.
- Demonstrar a solução proposta para o monitoramento dos animais.
- Divulgar o funcionamento e os objetivos do projeto.
- Facilitar o acesso às informações por meio de uma interface visual e intuitiva.

## ✨ Funcionalidades

O site possui uma estrutura de apresentação dividida em seções:

| Seção | Descrição |
|---|---|
| **Início** | Apresentação visual do projeto e sua identidade. |
| **Sobre** | Explicação sobre o BUBATAG e seus objetivos. |
| **Problemática** | Apresentação dos desafios relacionados ao manejo de bubalinos. |
| **Solução** | Demonstração da proposta tecnológica desenvolvida. |
| **Pitch** | Apresentação audiovisual do projeto. |
| **Navegação** | Menu com navegação entre as seções da página. |
| **Responsividade** | Adaptação da interface para diferentes tamanhos de tela. |

## 🛠️ Tecnologias utilizadas

O projeto utiliza tecnologias modernas para desenvolvimento de interfaces web.

| Tecnologia | Aplicação |
|---|---|
| [Next.js](https://nextjs.org/) | Framework para desenvolvimento da aplicação web. |
| [React](https://react.dev/) | Construção de interfaces por componentes. |
| [JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript) | Linguagem de programação. |
| [Tailwind CSS](https://tailwindcss.com/) | Estilização e construção do layout. |
| [AOS](https://michalsnik.github.io/aos/) | Animações durante a rolagem da página. |
| [React Icons](https://react-icons.github.io/react-icons/) | Biblioteca de ícones. |
| [Vercel](https://vercel.com/) | Hospedagem e publicação do site. |

## 💻 Como executar o projeto localmente

Siga as etapas abaixo para baixar, instalar as dependências e executar o projeto em seu computador.

### 1. Pré-requisitos

Antes de começar, certifique-se de possuir:

- **Node.js:** versão 20 LTS recomendada.
- **npm:** gerenciador de pacotes instalado junto com o Node.js.
- **Git:** para clonar o repositório.
- **Editor de código:** recomendamos o Visual Studio Code.

Você pode baixar as ferramentas pelos links:

- [Download do Node.js](https://nodejs.org/)
- [Download do Git](https://git-scm.com/)
- [Download do Visual Studio Code](https://code.visualstudio.com/)

Para verificar se as ferramentas estão instaladas, abra o terminal e execute:

```bash
node -v
npm -v
git --version
```

### 2. Clonar o repositório

Abra o terminal ou o PowerShell e execute:

```bash
git clone https://github.com/bubatag/bubatag-site.git
```

Entre na pasta do projeto:

```bash
cd bubatag-site
```

### 3. Instalar as dependências

Com o terminal aberto dentro da pasta do projeto, execute:

```bash
npm ci
```

Esse comando utiliza o arquivo `package-lock.json` para instalar as versões de dependências registradas no projeto, proporcionando uma instalação consistente.

Aguarde até que a instalação seja concluída.

### 4. Executar o projeto

Para iniciar o servidor de desenvolvimento, utilize:

```bash
npm run dev
```

Após a inicialização, acesse o endereço abaixo pelo navegador:

**http://localhost:3000**

Pronto! O site estará disponível localmente.

As alterações realizadas nos arquivos do projeto serão refletidas automaticamente durante o desenvolvimento.

### 5. Encerrar o servidor

Para interromper a execução do projeto, volte ao terminal e pressione:

```bash
Ctrl + C
```

## ⚙️ Scripts disponíveis

O projeto disponibiliza os seguintes comandos:

| Comando | Descrição |
|---|---|
| `npm run dev` | Inicia o servidor de desenvolvimento com Turbopack. |
| `npm run build` | Gera a versão de produção do projeto. |
| `npm start` | Inicia o servidor utilizando a versão de produção compilada. |
| `npm run lint` | Executa a análise estática do código com ESLint. |

### Executar em modo de produção

Caso queira testar a versão de produção localmente, execute:

**1. Gerar a compilação:**

```bash
npm run build
```

**2. Iniciar o servidor de produção:**

```bash
npm start
```

**3. Acessar pelo navegador:**

```text
http://localhost:3000
```

## 📁 Estrutura do projeto

O projeto segue a organização de diretórios do Next.js, separando os componentes, estilos e arquivos públicos.

```text
bubatag-site/
│
├── public/
│   ├── fonts/                  # Fontes utilizadas no site
│   └── imgs/                   # Imagens, vídeos e recursos visuais
│
├── src/
│   └── app/
│       ├── components/
│       │   ├── Navbar.js       # Menu de navegação
│       │   ├── Header.js       # Seção inicial
│       │   ├── Sobre.js        # Apresentação do projeto
│       │   ├── Problematica.js # Contextualização do problema
│       │   ├── Solucao.js      # Apresentação da solução
│       │   ├── Pitch.js        # Componente de apresentação audiovisual
│       │   ├── Footer.js       # Rodapé
│       │   └── AOSWrapper.js   # Inicialização das animações
│       │
│       ├── page.js             # Página principal
│       ├── layout.js           # Layout global da aplicação
│       └── globals.css         # Estilos globais
│
├── .gitignore
├── eslint.config.mjs
├── jsconfig.json
├── next.config.mjs
├── package.json
├── package-lock.json
├── postcss.config.mjs
├── tsconfig.json
└── README.md
```

**Observação:** a estrutura acima destaca os principais arquivos identificados no repositório. A pasta `public` também pode conter outros recursos utilizados pela aplicação.

## 🎨 Identidade visual

A identidade visual do site utiliza elementos gráficos e cores associados à proposta tecnológica e sustentável do BUBATAG.

Entre os elementos visuais estão:

- Tons de verde que representam tecnologia, natureza e sustentabilidade.
- Fundo em tons escuros para destacar os elementos da interface.
- Tipografia personalizada.
- Ilustrações e recursos audiovisuais.
- Animações para melhorar a experiência de navegação.

## 🎓 Sobre o desenvolvimento

O BUBATAG é um Projeto Integrador desenvolvido no curso de **Tecnologia em Desenvolvimento de Software Multiplataforma**, da Faculdade de Tecnologia de Registro (Fatec Registro), vinculada ao Centro Paula Souza.

O projeto integra conhecimentos de desenvolvimento de software, Internet das Coisas (IoT) e tecnologia aplicada ao agronegócio, buscando contribuir para a modernização da bubalinocultura.

**🐂 BUBATAG — Conectando tradição e inovação.**

*Tecnologia a serviço do bem-estar animal e da produção sustentável.*

[🌐 Acessar o site](https://bubatag-site.vercel.app/) · [💻 Repositório](https://github.com/bubatag/bubatag-site)

</div>
