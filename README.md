# Criando um Copilot com Fluxo de Conversa Personalizada no Microsoft Copilot Studio

Este guia descreve passo a passo como criar um copilot com um fluxo de conversa personalizado usando o **Microsoft Copilot Studio**. O objetivo é mostrar como iniciar um projeto do zero, customizar tópicos e mensagens, além de utilizar a inteligência generativa (GenAI) para melhorar a qualidade das respostas.

---

## 🧠 Requisitos

- Conta Microsoft com acesso ao Copilot Studio
- Navegador compatível (recomendado: Microsoft Edge ou Google Chrome)
- Conhecimentos básicos sobre fluxos conversacionais

---

## 🚀 1. Criar um Copilot em Branco

1. Acesse o [Microsoft Copilot Studio](https://copilotstudio.microsoft.com/).
2. Clique em **"Criar copilot"** no menu lateral.
3. Escolha a opção **"Criar um em branco"**.
4. Dê um nome ao seu copilot e clique em **"Criar"**.
5. Após a criação, você será direcionado para a área de design, onde poderá começar a personalizar os tópicos e fluxos.

---

## ✍️ 2. Customizar um Tópico

1. No menu lateral, vá até **"Tópicos"**.
2. Clique em **"Novo tópico"** ou edite um tópico existente.
3. Defina os **gatilhos** (palavras-chave ou frases que iniciam o tópico).
4. Adicione os **nós de mensagem**, **perguntas** e **condições lógicas** para construir o fluxo da conversa.
5. Você pode usar **expressões condicionais** ou conectar com APIs externas via ações para personalizar ainda mais o comportamento.

> 💡 Dica: Utilize variáveis para armazenar respostas do usuário e controlar a navegação entre os nós do tópico.

---

## ❌ 3. Personalizar uma Mensagem de Erro de Tópico

Quando o Copilot não entende ou falha ao processar um tópico, você pode personalizar a resposta de erro:

1. Vá até o tópico desejado e localize o nó de **mensagem padrão de erro**.
2. Altere o conteúdo para uma resposta mais amigável ou personalizada, como por exemplo:

```text
Desculpe, não consegui entender isso. Você pode reformular ou tentar outra opção? 🙂


