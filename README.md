# Criando um Copilot com Fluxo de Conversa Personalizada no Microsoft Copilot Studio

Como criei um copilot com um fluxo de conversa personalizado usando o Microsoft Copilot Studio. E o que pude aprender e absrover sobre o Copilot.

---

## 🧠 Requisitos

- Conta Microsoft com acesso ao Copilot Studio
- Navegador compatível 

---

## 🚀 1. Criar um Copilot em Branco

1. Acesse o Copilot.
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
```
3. Também é possível redirecionar o usuário para outro tópico a partir do erro, mantendo a conversa fluida.

## 🧬 4. Aumentar ou Diminuir a Qualidade da Resposta com GenAI

O Microsoft Copilot Studio permite incorporar respostas geradas por IA (GenAI) utilizando serviços como o Azure OpenAI. Para controlar a qualidade ou a criatividade da resposta:

Em um nó de mensagem, adicione uma ação do tipo "Chamar GenAI".

Configure o prompt da IA com instruções claras, por exemplo:

"Resuma este texto"

"Explique como se fosse para uma criança"

"Responda de forma profissional e objetiva"

Utilize os controles de temperatura, máximo de tokens e top-p (quando disponíveis) para ajustar o grau de criatividade e precisão:

Temperatura baixa (ex: 0.2) → respostas mais precisas e diretas.

Temperatura alta (ex: 0.8) → respostas mais criativas e abertas.

Você pode armazenar a resposta da GenAI em uma variável e usá-la dinamicamente em outras mensagens do fluxo.

---

✅ Conclusão
Ao seguir este guia, você foi capaz de:

Criar um copilot em branco no Microsoft Copilot Studio

Customizar tópicos com fluxos personalizados

Ajustar mensagens de erro para melhorar a experiência do usuário

Integrar e configurar respostas com GenAI para um conteúdo mais relevante e dinâmico
