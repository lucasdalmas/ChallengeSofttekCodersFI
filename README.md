# Helpdesk: Sua Solução Inovadora para Suporte Técnico

## Apresentação

Bem-vindo ao Helpdesk, a plataforma desenvolvida pela Coders.Fi que revoluciona o suporte técnico!

O Helpdesk utiliza o Gemini, um modelo de linguagem de Inteligência Artificial Generativa da Google, para oferecer um suporte interativo e personalizado, guiando o usuário por meio de diagnósticos, sugestões de solução e respostas a dúvidas técnicas em tempo real.

## Configurando o Helpdesk

Para acessar as funcionalidades do programa, é necessária uma Chave API da Google.

### Obtendo uma Chave API da Google:

1. Acesse o Google AI Studio com uma Conta Google: [https://aistudio.google.com](https://aistudio.google.com)
2. Selecione "Get API key".
3. Selecione "Criar chave de API" e Crie uma chave de API em um novo projeto.
4. Chave de API criada com sucesso!
5.Copie a sua chave API para utilizar no projeto.
6. Clique no texto azul abaixo de "Chave de API" (ex: …xPhk) e copie a chave API gerada.

### Configurando a Chave API no Projeto:

#### Back-End:

Ao rodar o código "ProjectAI.java", a primeira coisa que será requisitada no terminal é a chave API. Certifique-se de inserir a sua chave API corretamente.

#### Front-End + Back-End Integrado:

1. Antes de rodar o projeto, abra o arquivo "comunicacao_gemini.js" na aplicação FRONTEND dentro da pasta "\js" e substitua a String "YOUR_API_KEY" dentro da const API_KEY na linha 5 do código pela sua chave API.

```javascript
API_KEY = "YOUR_GOOGLE_API_KEY"
```

## Rodando a Aplicação

### Back-End:

1. Certifique-se de ter o Java instalado.
2. Navegue até a pasta do projeto Helpdesk.
3. Abra o projeto "Softtek AI API" na IDE IntelliJ.
4. Execute o Arquivo "ProjectAI.java" no endereço "\src\main\java\com\projetoAI\Project\AI\testes\Project.java". Esse código possui um método main que permite a visualização de chamados da Softtek e obter, por meio de IA Generativa, soluções para os problemas encontrados nos chamados.

### Front-End + Back-End Integrado:

1. Certifique-se de possuir a extensão Live Server.
    * Caso não possua, siga os passos a seguir para instalar a extensão:
        1. Abra o Visual Studio Code.
        2. Acesse as Extensões na Barra Lateral (ou Ctrl+Shift+X).
        3. Pesquise Live Server.
        4. Instale a Extensão Live Server de "Ritwick Dey".
        5. Habilite a Extensão.
2. Navegue até a pasta do projeto Front-End do Helpdesk.
3. Abra o projeto "Softtek AI API" na IDE IntelliJ.
4. Execute o Arquivo "ProjectAiApplication.java" no endereço "\src\main\java\com\projetoAI\Project\AI\ProjectAiApplication.java".
5. Instale as dependências do projeto (se necessário).
6. Abra o projeto "Softtek AI Front" na IDE Visual Studio Code.
7. Clique em Go Live no canto Inferior Esquerdo do Visual Studio Code para iniciar o Run Live Server.

## Acessando o Helpdesk

1. Abra seu navegador e acesse o endereço do servidor de desenvolvimento do Front-End. Um exemplo de porta gerada é `http://127.0.0.1:5501/`.
2. Utilize as credenciais de acesso para logar na plataforma. As páginas da aplicação só permitem ser acessadas após ter feito o login. Caso não tenha nenhum acesso, verifique dentro de `src/main/resources/usuarios/usuarios.json`, e utilize uma das credenciais possíveis. Exemplo:

### Acessando os Chamados

1. Clique em "Meus Chamados". Essa é a tela que apresenta os chamados da Softtek para o suporte de TI.

### Realizando um chamado no Helpdesk com a Côda:

1. Acesse os chamados em "Meus Chamados" e copie o número do chamado que deseja receber o auxílio da Côda.
2. Vá em "Início" e "Abrir Chamado".
3. Clique no campo "Mensagem" e cole o Número do chamado desejado.

**Observação:** Este guia assume que você já possui familiaridade com o desenvolvimento em Java e JavaScript. Em caso de dúvidas, consulte a documentação oficial do Java e JavaScript ou procure suporte técnico especializado.
