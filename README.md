# Connect+ | Plataforma de Comunicação (Seed by DeepSeek AI)

## 📝 Descrição

**Connect+** é uma plataforma web de comunicação interna, cujo código inicial foi gerado pela IA DeepSeek como um estudo de caso. O objetivo é fortalecer a cultura de feedback em ambientes corporativos, permitindo que colaboradores enviem elogios, sugestões e críticas de forma transparente e colaborativa.

A aplicação, originalmente contida em um único arquivo, foi refatorada para uma estrutura modular e escalável, demonstrando boas práticas de organização de código. O projeto conta com diferentes níveis de acesso (Colaborador, Gerente, RH e CEO).

---

## ⚙️ Principais Funcionalidades

- **Autenticação:** Sistema de login e cadastro com diferentes perfis e permissões.
- **Dashboard Interativo:** Visualização de estatísticas, feedbacks recentes e ranking de colaboradores.
- **Envio de Feedback:** Formulário para envio de elogios, sugestões e críticas, com opção de anonimato.
- **Histórico Pessoal:** Tela para o usuário visualizar todos os feedbacks que já enviou.
- **Painel de RH (Acesso Restrito):** Gerenciamento de funcionários e visualização de estatísticas gerais da empresa.

---

## 💻 Tecnologias e Linguagens Utilizadas

- **Frontend:**
    - **HTML5:** Estruturação semântica.
    - **Tailwind CSS:** Framework CSS (via CDN).
    - **JavaScript (Vanilla):** Lógica da aplicação, dividida em módulos para melhor organização.
- **Ícones:**
    - **Font Awesome:** Biblioteca de ícones.
- **Origem do Código:**
    - **DeepSeek AI:** Geração do código base inicial.

---

## 📁 Estrutura de Pastas e Arquivos

Para tornar o projeto mais profissional e fácil de manter, o código original foi refatorado para a seguinte estrutura:

```
/
├── index.html              # Estrutura principal da página
├── css/
│   └── style.css           # Estilos customizados
└── js/
    ├── main.js             # Ponto de entrada, inicializa a aplicação
    ├── ui.js               # Funções que manipulam o DOM (telas, modais)
    ├── auth.js             # Lógica de autenticação (login, cadastro, logout)
    └── data.js             # Simulação do "banco de dados" (arrays de dados)
```
- **`index.html`**: Contém apenas a estrutura HTML e os links para os arquivos CSS e JS.
- **`css/style.css`**: Armazena as regras de estilo que antes estavam na tag `<style>`.
- **`js/`**: Pasta que contém os scripts divididos por responsabilidade, tornando o código mais legível e manutenível.

---

## ▶️ Passo a Passo de Execução

1.  Clone o repositório:
    ```bash
    git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
    ```
2.  Navegue até a pasta do projeto:
    ```bash
    cd seu-repositorio
    ```
3.  Abra o arquivo `index.html` diretamente em seu navegador.

A aplicação carregará e você poderá interagir com as contas de teste pré-configuradas.
