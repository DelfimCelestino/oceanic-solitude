```markdown
# Bem-vindo à sua Extensão Oceanic Solitude para VS Code

## O que há na pasta

* Esta pasta contém todos os arquivos necessários para sua extensão de tema de cores.
* `package.json` - este é o arquivo de manifesto que define a localização do arquivo de tema e especifica o tema base.
* `themes/oceanic-solitude-color-theme.json` - o arquivo de definição do tema de cores.

## Comece a usar imediatamente

* Pressione `F5` para abrir uma nova janela com sua extensão carregada.
* Abra o seletor de tema de cores com o item de menu `Arquivo > Preferências > Tema > Tema de Cores`, ou use o comando `Preferências: Tema de Cores (Ctrl+K Ctrl+T)` e escolha o tema Oceanic Solitude.
* Abra um arquivo que tenha uma linguagem associada. A gramática configurada das linguagens tokenizará o texto e atribuirá 'escopos' aos tokens. Para examinar esses escopos, invoque o comando `Desenvolvedor: Inspecionar Tokens e Escopos do Editor` na Paleta de Comandos (`Ctrl+Shift+P` ou `Cmd+Shift+P` no Mac).

## Faça alterações

* As alterações no arquivo de tema são aplicadas automaticamente à janela do Host de Desenvolvimento de Extensão.

## Adapte seu tema ao Visual Studio Code

* A colorização dos tokens é feita com base em temas TextMate padrão. As cores são correspondidas a um ou mais escopos.

Para saber mais sobre escopos e como eles são usados, confira a documentação sobre [tema de cores](https://code.visualstudio.com/api/extension-guides/color-theme).

## Instale sua extensão

* Para começar a usar sua extensão com o Visual Studio Code, copie-a para a pasta `<home do usuário>/.vscode/extensions` e reinicie o Code.
* Para compartilhar sua extensão com o mundo, leia em https://code.visualstudio.com/docs sobre como publicar uma extensão.

## Personalizando o Oceanic Solitude

O tema Oceanic Solitude foi projetado para evocar a sensação de tranquilidade das profundezas do oceano. Se você quiser fazer ajustes:

1. Abra o arquivo `themes/oceanic-solitude-color-theme.json`.
2. Modifique as cores conforme necessário. Por exemplo, para ajustar a cor de fundo do editor:

   ```json
   "editor.background": "#001a2c"
```

3. Para uma referência completa de todas as configurações de cores disponíveis, consulte a [documentação oficial do VS Code](https://code.visualstudio.com/api/references/theme-color).


Lembre-se de que cada mudança que você fizer afetará a experiência geral do tema, então faça alterações com cuidado para manter a coesão visual do Oceanic Solitude.