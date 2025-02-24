# Criando resposta generativas com IA no Copilot Studio

## O que é Resposta Generativa?

- São conteúdos adicionados baseados no LLMs considerando alguns dados fornecidos pelo usuário e toda a base de conhecimento do modelo.

- O Copilot Studio suporta diversos tipos da dados como:
    - word, excel, powerpoint, pdf, txt, html, csv, xml, epub, rtf, json, entre outros.

- Tem também as opções de gerar **Ações e Plugins**, mas no entanto não estão disponíveis em português, apenas em inglês.
    - As **ações** possuem praticamente as mesmas funções dos **tópicos**
        - A difenrença é que as ações são sempre conteúdos dinâmicos por conta de IA Generativa,l informando para a própria IA reconhecer o comportamento esperado do usuário e o que precisa para continuar o fluxo.
        - Ex =>  + usuário: "Quero buscar a ordem XXx"

                 + IA generativa: "retorna um JSON com os dados esperados"

## Como encontrar essa configuração no Copilot Studio?

- Basta ir no tópico desejado e inserir um bloco para adicionar "Generative answers"


![alt text](image-12.png)


- No bloco de Respostas Generativas terá um campo para inserir uma variável ou um texto
    - Por padrão, no tópico **Generative boosting** é passado como variável no bloco o "**Activity.Text**"
        - Ela informa a última mensagem do usuário
    - Além disso, há várias propriedades, até conseguir inserir uma base de dados que a IA pode consultar para se basear e dar uma resposta no mesmo sentido.

- Para acessar a página de **Ações** é preciso habilitar a opção **Generative IA** que fica dentras configurações do agente.
    - Infelizmente essa opção só pode ser habilitada na linguagem em inglês.

- Com as actions é possível usar 'plugins' que direcionados a determinadas funcionalidades usando IA para auxiliar a reconhcer as requisições do usuário e ativar a ação.

## Conceitos importantes de GenAI no Copilot

1 - Balanceamento de Conteúdo
    

## Como definir as melhoras configurações para resposta para a aplicação

## O que são Knowledge Sources?