# Conventional Commits Reminder

Tipos:

*feat* - Um novo recurso

*fix* - Correção de bug

*refactor* - Uma alteração de código que não corrige um bug nem adiciona um recurso

*chore* - Outras alterações que não modificam src ou arquivos de teste

*docs* - Apenas muda a documentação

*style* - Alterações que não afetam o significado do código (espaço em branco, formatação, ponto e vírgula ausente etc.)

*perf* - Uma alteração de código que melhora o desempenho

*test* - Adicionando testes ausentes ou corrigindo testes existentes

*build* - Alterações que afetam o sistema de compilação ou dependências externas (escopos de exemplo: gulp, broccoli, npm)

*ci* - Alterações nos arquivos e scripts de configuração do IC (escopos de exemplo: Travis, Circle, BrowserStack, SauceLabs)

*revert* - Reverte uma confirmação anterior

---

Padrão:

```
<tipo> [escopo opcional]: <descrição> 
[corpo opcional] 
[rodapé opcional]
```

Exemplo real:
```
git commit -m "feat (página inicial): adicione rodapé alternativo à página inicial

Implemente a versão alternativa do rodapé 

Adicione ícones alternativos na versão móvel do rodapé 
Corrige o problema nº 3"
```
