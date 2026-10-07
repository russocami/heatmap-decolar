# Heatmap Decolar - Colaboradores SP

Mapa interativo com a distribuição de colaboradores da Decolar no estado de São Paulo.

## 🗺️ Acessar

Acesse em: `https://seu-usuario.github.io/heatmap-decolar`

(Substitua `seu-usuario` pelo seu username do GitHub)

## 📦 Como usar

### Opção 1: Criar do zero (mais fácil)

1. Vá em https://github.com/new
2. Nome do repo: `heatmap-decolar`
3. Marque "Add a README file"
4. Clique "Create repository"
5. Abra o repo, clique em "Add file" → "Upload files"
6. Arraste os arquivos `index.html` e `README.md` aqui
7. Clique "Commit changes"
8. Vá em Settings → Pages → Source: main branch
9. Pronto! Vai estar disponível em: `https://seu-usuario.github.io/heatmap-decolar`

### Opção 2: Linha de comando (mais rápido)

```bash
# Clone o repo vazio que você criou
git clone https://github.com/seu-usuario/heatmap-decolar
cd heatmap-decolar

# Copie os arquivos index.html e README.md pra essa pasta

# Suba
git add .
git commit -m "Add heatmap"
git push
```

## 📊 Dados

- **Total Estado de SP**: 779 colaboradores
- **São Paulo (Capital)**: 372 (47.8%)
- **Grande SP (Cinturão)**: 219 (28.1%)
  - Osasco: 71
  - Guarulhos: 68
  - Barueri: 41
  - Carapicuíba: 29
  - Outros: 10
- **ABC Paulista**: 61 (7.8%)
- **Interior**: 127 (16.3%)
- **Litoral**: 7 (0.9%)
- **Cidades**: 52 com colaboradores

## 🎨 Cores

- 🔴 **Vermelho escuro**: 250+ colaboradores
- 🟠 **Laranja**: 50-250 colaboradores  
- 🟡 **Amarelo**: 20-50 colaboradores
- 🟢 **Verde**: 5-20 colaboradores
- 🔵 **Azul**: menos de 5 colaboradores

## 💡 Interatividade

- **Passar o mouse**: vê a cidade e quantidade
- **Clicar no círculo**: abre popup com detalhes
- **Scroll/pinch**: zoom in/out
