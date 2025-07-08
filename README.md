# Connect+ | Plataforma de Comunicação e Feedback Corporativo

## 📝 Descrição

**Connect+** é uma plataforma web de comunicação interna projetada para fortalecer a cultura de feedback em ambientes corporativos. Através dela, os colaboradores podem enviar elogios, sugestões e críticas construtivas, de forma anônima ou identificada, promovendo um ambiente de trabalho mais transparente e colaborativo.

A aplicação conta com diferentes níveis de acesso (Colaborador, Gerente, RH e CEO), garantindo que as informações sensíveis sejam acessadas apenas por quem tem permissão.

---

## ⚙️ Principais Funcionalidades

- **Autenticação:** Sistema de login e cadastro de usuários com perfis e permissões.
- **Dashboard Interativo:** Visualização rápida de estatísticas pessoais, como elogios recebidos, feedbacks enviados e um ranking de colaboradores.
- **Envio de Feedback:** Formulário intuitivo para enviar:
    - **Elogios:** Reconheça o bom trabalho dos colegas.
    - **Sugestões:** Proponha melhorias para a empresa.
    - **Críticas Construtivas:** Forneça feedbacks para o desenvolvimento profissional.
- **Envio Anônimo:** Opção para garantir a privacidade do remetente.
- **Histórico:** Tela para o usuário visualizar todos os feedbacks que já enviou.
- **Painel de Reconhecimento:** Destaques como "Colaborador do Mês", "Mais Elogiado" e os últimos elogios públicos.
- **Painel de RH (Acesso Restrito):**
    - Gerenciamento completo de funcionários (adicionar, editar, remover).
    - Visualização de estatísticas gerais da empresa.
    - Acesso a relatórios e gráficos sobre o engajamento e tipos de feedback.

---

## 💻 Tecnologias e Linguagens Utilizadas

- **Frontend:**
    - **HTML5:** Estruturação semântica do conteúdo.
    - **Tailwind CSS:** Framework CSS para estilização rápida e responsiva.
    - **JavaScript (Vanilla):** Manipulação do DOM, lógica da aplicação e interatividade.
- **Ícones:**
    - **Font Awesome:** Biblioteca de ícones vetoriais.

---

## 📁 Estrutura de Pastas e Arquivos

O projeto está estruturado como uma **Single Page Application (SPA)**, onde toda a interface e lógica rodam em um único arquivo:

```
/
└── index.html
```

- `index.html`: Contém a estrutura HTML, os estilos CSS (via CDN do Tailwind) e todo o código JavaScript que gerencia as telas, dados e interações do usuário.

---

## ▶️ Passo a Passo de Execução

Como este é um projeto front-end autocontido, não há necessidade de um servidor ou de instalar dependências.

1.  Clone o repositório:
    ```bash
    git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
    ```
2.  Navegue até a pasta do projeto:
    ```bash
    cd seu-repositorio
    ```
3.  Abra o arquivo `index.html` diretamente em seu navegador de preferência (Google Chrome, Firefox, etc.).

A aplicação carregará e você poderá interagir com as contas de teste pré-configuradas na tela de login.
