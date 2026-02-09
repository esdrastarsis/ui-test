# Facebook 2 - Sistema de Login

Este projeto é uma implementação de um sistema de login front-end. O objetivo é demonstrar como escolhas de design e feedback visual podem criar uma experiência de usuário (UX) robusta sem a necessidade de um backend complexo.

- Como Executar

    Baixe o código (ou copie o bloco acima).

    Salve como index.html.

    Abra o arquivo em qualquer navegador moderno (Chrome, Firefox, Edge).

    Credenciais para teste:

        ID: admin
        Senha: 1234

### Metas de Usabilidade:
- Fácil de lembrar (Learnability):

        * Utiliza o padrão universal de dois campos (usuário/senha).
        * Os rótulos (labels) flutuam, garantindo que o usuário sempre saiba o que está preenchendo, mesmo após clicar no campo.

- Fácil de entender (Understandability):

        * Interface limpa, sem distrações.
        * Botão de ação com texto claro ("Iniciar Conexão").
        * Feedback de erro explícito ("Credenciais Inválidas").

- Útil (Utility):

        * Cumpre a função de restringir acesso (simulado).

        * Permite visualizar a senha (toggle), útil para evitar erros de digitação.

- Seguro (Percepção do Usuário):

        * A senha é ocultada por padrão (asteriscos).
        * Existe um "delay" artificial de 1.5s.

- Eficiente:

        * Suporte à navegação por teclado (Tab para trocar campos, Enter para enviar).
        * Foco automático visual nos campos ativos.

### Metas de Experiência

- Esteticamente Apreciável:

        * Uso de Glassmorphism (efeito de vidro fosco).
        * Paleta de cores Neon/Cyberpunk (Ciano e Azul profundo).
        * Animações sutis de brilho (glow).

- Divertido / Imersivo:

        * O tema "Espacial" tira o tédio de um formulário bancário comum.
        * O jargão utilizado ("ID do Operador", "Biometria") contribui para o roleplay.

- Satisfatório:

        * Transições suaves (CSS transitions) em todos os elementos interativos.
        * A tela de sucesso preenche o card suavemente, dando uma sensação de conclusão.

- Emocionalmente Adequado (Confiança):

        * O design escuro e estruturado passa seriedade, apesar de ser temático. Não parece "infantil", mas sim uma ferramenta de controle.

- Interessante:

        * A animação de "Shake" (tremer) quando a senha está errada é um feedback instintivo que humaniza a resposta do sistema (como alguém balançando a cabeça negativamente).

### Tecnologias Utilizadas

- HTML5: Estrutura semântica.
- CSS3: Variáveis (Custom Properties), Flexbox, Animações Keyframes e Backdrop-filter.
- JavaScript (ES6): Manipulação do DOM, validação lógica e simulação de assincronismo (setTimeout).
