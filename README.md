# Caderno Temático: React com TypeScript utilizando NotebookLM

## Sobre o Projeto

Este projeto foi desenvolvido como parte do desafio proposto pela DIO com o objetivo de explorar o uso da Inteligência Artificial como ferramenta de aprendizagem ativa através do NotebookLM.

O tema escolhido foi **React com TypeScript**, uma das combinações mais utilizadas atualmente no desenvolvimento Front-End moderno. Durante o estudo, foram utilizadas fontes oficiais da documentação, técnicas de engenharia de prompts e processos de curadoria de conteúdo para consolidar o aprendizado.

---

# Objetivos de Estudo

- Compreender os fundamentos do React.
- Entender o funcionamento de componentes.
- Aprender a utilizar TypeScript em aplicações React.
- Aplicar tipagem em Props, States e Eventos.
- Conhecer os principais Hooks do React.
- Desenvolver boas práticas para projetos Front-End.
- Utilizar IA como apoio ao aprendizado sem substituir a análise crítica.

---

# Curadoria de Fontes

## React

### Documentação Oficial React

https://react.dev

### Learn React

https://react.dev/learn

## TypeScript

### Documentação Oficial TypeScript

https://www.typescriptlang.org/docs

### TypeScript Handbook

https://www.typescriptlang.org/docs/handbook/intro.html

## Ferramentas Complementares

### Vite

https://vitejs.dev/guide

---

# Engenharia de Prompts

## Prompt 1

Explique o que é React para alguém que já desenvolve aplicações PHP.

### Resultado

A IA apresentou uma comparação entre páginas renderizadas no servidor e interfaces baseadas em componentes.

### Aprendizado

Facilitou a compreensão da diferença entre aplicações tradicionais e Single Page Applications (SPA).

---

## Prompt 2

Explique Props e State utilizando exemplos práticos em TypeScript.

### Resultado

Foram apresentados exemplos tipados e comparações entre dados externos (Props) e internos (State).

### Aprendizado

Melhor entendimento do fluxo de dados entre componentes.

---

## Prompt 3

Mostre exemplos de uso do Hook useState utilizando TypeScript.

### Resultado

Exemplos com string, number, boolean, arrays e objetos.

### Aprendizado

Maior familiaridade com a tipagem de estados.

---

## Prompt 4

Quais são os erros mais comuns cometidos por iniciantes em React com TypeScript?

### Resultado

Foram identificados problemas frequentes como:

- Uso excessivo de any.
- Props sem tipagem.
- Eventos sem tipos definidos.
- Estados iniciados incorretamente.

### Aprendizado

Compreensão de boas práticas para evitar erros futuros.

---

# Cicatrizes e Troubleshooting

## Problema 1

As respostas utilizavam JavaScript puro ao invés de TypeScript.

### Solução

Passar a informar explicitamente:

"Utilize exclusivamente TypeScript nos exemplos."

## Problema 2

As respostas eram muito resumidas.

### Solução

Utilizar prompts mais específicos:

"Explique detalhadamente como se estivesse ensinando um desenvolvedor júnior."

## Problema 3

Muitos conceitos eram apresentados simultaneamente.

### Solução

Dividir o aprendizado em tópicos menores:

- Componentes
- Props
- State
- Hooks
- Eventos
- Tipagem

---

# Miniguia de Estudos

## O que é React?

React é uma biblioteca JavaScript criada para construção de interfaces de usuário baseadas em componentes reutilizáveis.

## O que é TypeScript?

TypeScript é um superset do JavaScript que adiciona tipagem estática ao código.

## React + TypeScript

A união das duas tecnologias proporciona:

- Componentes mais seguros
- Melhor experiência de desenvolvimento
- Maior escalabilidade
- Redução de bugs

## Componentes Tipados

```tsx
type ButtonProps = {
  title: string;
};

function Button({ title }: ButtonProps) {
  return <button>{title}</button>;
}
```

## Utilizando useState

```tsx
import { useState } from 'react';

function App() {
  const [nome, setNome] = useState<string>('');
}
```

---

# Glossário

- Component: Bloco reutilizável de interface.
- Props: Dados recebidos por um componente.
- State: Dados internos gerenciados pelo componente.
- Hook: Funções especiais fornecidas pelo React.
- useState: Hook utilizado para gerenciamento de estado.
- useEffect: Hook utilizado para efeitos colaterais.
- Interface: Estrutura utilizada para definir tipos.
- Generic: Tipo parametrizado reutilizável.

---

# Conclusão

O NotebookLM demonstrou ser uma ferramenta extremamente útil para consolidar conhecimento técnico através da combinação de documentação oficial, engenharia de prompts e organização estruturada de informações.
