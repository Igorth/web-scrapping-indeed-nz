# Web Scraping Indeed NZ

## Objetivo
Criar um crawler para coletar informações de ofertas de emprego no site [Indeed](https://nz.indeed.com/).
Informações coletadas:
- Título da oferta;
- Nome da empresa;
- Localização;
- Data que a oferta foi publicada;
- Link da oferta.

## Conclusão
Utilizando a biblioteca BeautifulSoup consegui coletar todas as informações que buscava e no final salvei em um DataFrame para melhor visualização.

## Caso queira usar
Estou utilizando o Anaconda para fazer o download das bibliotecas, [aqui](https://paulovasconcellos.com.br/como-baixar-anaconda-31fd49c19bd8) tem um tutorial caso queira instalar.
Basta alterar a URL do Indeed que deseja buscar ('https://nz.indeed.com/jobs?q=&l=Queenstown%2C+Otago') e rodar as células do Jupyter Notebook.
