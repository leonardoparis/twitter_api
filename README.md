# umfuteboldeemocoes
Desenvolvi o projeto Um Futebol de Emoções para estudar análise de textos e sentimentos em Python e compartilhar os resultados com a comunidade. É também um laboratório de experimentos em visualizações de texto e oportunidade de aprender o Git.

Fique à vontade para copiar, utilizar e melhorar o código. Para executá-lo, você precisará de:

    Uma conta google com Drive e Colab ativados
    
    Arquivos csv disponibilizados aqui lá no Drive:
    
        times_do_brasileirao.csv - arquivo com as informações do jogo de cada time na primeira rodada com campos 
        nome do time, perfil do Twitter,data e hora de início e fim de cada jogo

        times_do_brasileirao-cores.csv - arquivo com o nome do time e o código do colormap para desenhar os 
        wordclouds personalizados para cada time
    
    Uma conta de desenvolvedor no Twitter para Desenvolvedores:
    https://developer.twitter.com/en/apply/user.html

Leia o post no www.dadoslivres.blog e acompanhe as futuras publicações para ficar por dentro do Projeto:

    Introdução
    Google Drive+Colab
    A Estrutura de um Tweet
    Transmissões de Futebol no Twitter
    A Twitter API V2
    Fluxo de Extração e Tratamento dos Tweets
    Os Emojis
    WordClouds em Python
    Análise de Sentimentos
    Visualizando as emoções no Tableau
    Modelos

Atualmente estou trabalhando nas seguintes atualizações:

    Automatização:
        Cadastro das demais rodadas e seleção automática dos jogos a partir da data de execução do código
        Geração de dois tipos de imagens no Google Drive, via api: thumbnails e aumentada
        Criação do código HTML para a tabela na página de galeria de Wordclouds com as imagens e links 
        para as versões aumentadas, o que permitirá a atualização a cada rodada ser um simples copy e paste. 

    Visualização:
        Criação de colormaps melhores para as letras não ficarem tão claras
