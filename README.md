# Curso de Git e GitHub

Repositório de prática do curso de Git e GitHub. Aqui eu treino o fluxo do dia a dia de quem desenvolve em equipe:

- criar branches e commits
- abrir e mergear Pull Requests
- resolver conflitos
- usar `.gitignore`
- colaborar com outras pessoas (commits co-autorados)

## Estrutura

| Caminho | Descrição |
| --- | --- |
| `index.html` | Página simples usada nos exercícios de PR |
| `script.js` | Script de teste |
| `cadastro-cliente/` | Exercício de cadastro de cliente |
| `dir/` | Exercício com diretórios |

## Fluxo de trabalho

```bash
git checkout -b minha-branch
git add .
git commit -m "Descreve a mudança"
git push -u origin minha-branch
# abrir o Pull Request no GitHub e dar merge
```
