## 📦 Gerenciadores Python: pipx e poetry

###  pipx

*pipx* é uma gerenciador de pacotes similar ao pip, com a diferença que ele cria um ambiente virtual sem sujar as bibliotecas, isolando dentro dele. Faciliatando a instalação de pacotes globais.

```bash
sudo apt install pipx
pipx ensurepath  # Comando pra adicionar o pipx ao PATH
```
### poetry

O poetry gerenciador de projetos para python , auxiliando em diversas etapas do desenvolvimento. Como instalação de versões do Python por exemplo.
```bash
pipx install poetry 
poetry self add poetry-plugin-shell (Habilita o Ambiente Virtual)
```
### Criando um Projeto
```bash
poetry new --flat nomeprojeto (cria um projeto no formato flat, mas por padrão é src.)
```
Diferenças entre o flat e o src : https://packaging.python.org/en/latest/discussions/src-layout-vs-flat-layout/
