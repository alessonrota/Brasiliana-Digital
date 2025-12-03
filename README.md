# Brasiliana-Digital

## Algoritmo para coleta e analíse da https://brasilianadigital.com.br/


Instalação e configuração


Instale as dependências necessárias:
  
  
  O script usa o módulo requests_html, que pode ser instalado através do pip. Para instalá-lo, abra o terminal e execute o seguinte comando:

`pip install requests_html`


1 - Abra o script:
    Abra o script em um editor de texto como o VSCode ou o Sublime Text. Certifique-se de que todas as dependências foram importadas corretamente.

2 - Defina os valores de start e do loop for:
    O valor de start é a primeira página do livro que você deseja baixar. Defina este valor como 0 para baixar todas as páginas. O loop for que começa na linha 49 define o intervalo de IDs dos livros que você deseja baixar. Altere os valores de range conforme necessário para baixar livros diferentes.

3 - Execute o script:
    Salve o script e execute-o no terminal. O script exibirá informações sobre o progresso do download e, se houver algum erro, exibirá mensagens de erro. As imagens baixadas serão salvas em uma pasta chamada brasiliana, com uma subpasta para cada livro, nomeada com o ID do livro.
