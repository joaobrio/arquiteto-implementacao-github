# System Prompts - Arquiteto de Implementação GitHub

## 🧠 O que são System Prompts?

System prompts são instruções especializadas que transformam o Claude (ou outra IA) em um especialista específico. É como dar um roteiro detalhado a um ator - ele saberá exatamente como se comportar, que conhecimento aplicar e como abordar cada situação.

## 📚 Prompts Disponíveis

### 1. [Arquiteto Principal](./arquiteto-principal.md)
O prompt principal do sistema, otimizado para migrações complexas de documentação.

### 2. [Analista de Estrutura](./analista-estrutura.md) 
Especializado em analisar e mapear estruturas documentais existentes.

### 3. [Conversor Markdown](./conversor-markdown.md)
Focado em conversão de alta qualidade para formato Markdown.

## 🎯 Como Usar

### No Claude Web/Desktop

1. **Copie o prompt desejado**
2. **Cole no início de uma nova conversa**
3. **Adicione seu pedido específico**

### Exemplo de Uso

```
[Cole o System Prompt aqui]

Agora, preciso migrar o documento "Política de Segurança" do Google Drive para o formato Markdown, mantendo toda a estrutura e criando navegação interna.
```

## 🔧 Personalizando Prompts

Cada prompt pode ser ajustado para necessidades específicas:

- **Adicione contexto**: Informações sobre sua organização
- **Especifique padrões**: Seus guias de estilo específicos
- **Defina restrições**: Limitações ou requisitos especiais

## 📊 Melhores Práticas

1. **Use prompts completos**: Não tente resumir - a precisão vem do detalhe
2. **Mantenha consistência**: Use o mesmo prompt para tarefas similares
3. **Documente adaptações**: Se modificar um prompt, documente o motivo
4. **Teste antes de produzir**: Valide com documentos de teste primeiro

## 📦 Estrutura de um System Prompt

Todo prompt bem construído contém:

```xml
<role>
  Definição clara do papel e expertise
</role>

<context>
  Informações de background necessárias
</context>

<capabilities>
  Lista de capacidades e responsabilidades
</capabilities>

<methodology>
  Processo passo-a-passo de trabalho
</methodology>

<output-format>
  Formato esperado das respostas
</output-format>

<principles>
  Princípios orientadores e valores
</principles>
```

## 🔄 Evolução Contínua

Estes prompts evoluem com o uso. Contribua com melhorias baseadas em sua experiência!