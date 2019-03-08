# motivate-discovery
Utilizando Python para compreender dados de um serviço de compartilhamento de bicicletas nos EUA.

## Visão geral
Neste projeto, utilizou-se Python para explorar dados relacionados aos sistemas de compartilhamento de bicicletas presente nas três maiores cidades dos Estados Unidos: Chicago, Nova Iorque e Washington. Foi feito um código para importar dados e responder a perguntas interessantes sobre eles, por meio da computação de estatísticas descritivas. 

## Dados sobre compartilhamento de bicicletas
Na última década, os sistemas de compartilhamento de bicicletas têm crescido em número e popularidade nas cidades de todo o mundo. Sistemas de compartilhamento de bicicletas permitem que os usuários aluguem bicicletas por um período curtíssimo, por um preço específico. Isso permite que pessoas retirem uma bicicleta do ponto A e a devolvam no ponto B, embora também possam devolvê-la no mesmo local, caso queiram apenas sair para um passeio. Independentemente disso, cada bicicleta pode servir vários usuários por dia.
Graças à ascensão das tecnologias de informação, é fácil para um usuário acessar uma estação dentro do sistema para desbloquear ou devolver as bicicletas. Essas tecnologias também fornecem uma riqueza de dados que podem ser utilizados para explorar como esses sistemas de compartilhamento de bicicletas são usados.
Neste projeto, utilizou-se os dados fornecidos pelo  [Motivate](https://www.motivateco.com/) , um provedor de sistema de bicicletas compartilhadas para diversas grandes cidades dos Estados Unidos, para descobrir os padrões de uso do compartilhamento de bicicletas. Analisou-se o uso do sistema de uma das maiores cidades dos Estados Unidos: Chicago.

## Os conjuntos de dados
Os dados para os primeiros seis meses de 2017 são fornecidos. O arquivo de dados contêm **seis (6)** colunas principais:
* Horário de início (ex., 2017-01-01 00:07:57)
* Horário de término (ex., 2017-01-01 00:20:53)
* Duração da viagem (em segundos, ex., 776)
* Estação inicial (ex., Broadway & Barry Avenue)
* Estação final (ex., Sedgwick St & do North Ave)
* Tipo de usuário (assinante ou cliente)
* Gênero do usuário
* Ano de nascimento do usuário

Os arquivos originais - que podem ser acessados aqui:  [Chicago](https://www.divvybikes.com/system-data) ,  [Nova Iorque](https://www.citibikenyc.com/system-data)  e  [Washington](https://www.capitalbikeshare.com/system-data)  - tinham mais colunas, e elas diferiam em formato em muitos casos. Alguns processos de  [data wrangling](https://en.wikipedia.org/wiki/Data_wrangling)  foram realizados para condensar esses arquivos nas seis colunas principais citadas acima, para simplificar sua análise e a avaliação de suas habilidades de Python. 

[Dataset (Chicago)](https://drive.google.com/file/d/1uBz6mGUmu5YctJjMkjZhKvD3jgNwhtBL/view?usp=sharing)
