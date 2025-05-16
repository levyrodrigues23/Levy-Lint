# 🔍 Levy Linter

Uma extensão do VS Code feita por Levy — o cara brabo — pra te alertar de erros e más práticas no código.  
Chega de usar `var` por aí, mermão! A extensão te avisa quando tu fizer besteira.

## 🚀 Funcionalidades

- Detecta o uso de `var` e te dá um puxão de orelha.
- Identifica sintaxes suspeitas e manda aquele alerta maroto.
- Ajuda a manter o código limpo, no estilo Levy de qualidade. 💅

## 🛠️ Como usar

1. Instala a extensão (ou roda ela com `F5` em modo dev).
2. Abre qualquer arquivo de código (por enquanto, funciona melhor com `.js`, `.ts`, etc).
3. Pressiona `Ctrl + Shift + P` e procura por **"Levy Linter"**.
4. A extensão vai analisar o código e te mostrar alertas, caso encontre algum vacilo.

## 📦 Exemplo de alerta

⚠️ Levy avisa: sai fora com esse 'var', usa let ou const, man!

## 📁 Estrutura atual (simplificada)

```
levy-linter/
├── .vscode/
├── src/
│   └── extension.ts
├── package.json
├── tsconfig.json
└── README.md
```

## ✨ Futuras melhorias

- Destacar os erros diretamente no editor.
- Suporte a outras linguagens além de JS/TS.
- Configurações personalizadas (pra escolher o tipo de alerta).
- Análise automática ao salvar o arquivo.

## 🙌 Feito com carinho por [Levy](https://github.com/seu-usuario)

Gostou da extensão? Manda um salve e contribui com sugestões!
