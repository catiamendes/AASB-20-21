# AASB-20-21
Algoritmos para Análise de Sequências Biológicas 20/21

Ficha 4

Algoritmos para Análise de Sequências Biológicas

Crie um projeto Github para o seu grupo. Este projeto irá crescer ao longo das aulas
Este trabalho será feito em grupos de 4 pessoas
Inscreva o seu grupo aqui: https://forms.gle/XCbcDUiH6mtJ3KhCA

Crie um módulo para armazenar as suas funções sobre sequências. 
O seu módulo deve providenciar as seguintes funções:

ler_seq(FileHandle) Função que recebe um ficheiro aberto e que devolve uma sequência

ler_FASTA_seq(FileHandle) Função que recebe um ficheiro aberto e que devolve uma sequência

complemento_inverso(seq) Função que devolve o complemento inverso de uma sequência de DNA

transcricao(seq) Função que devolve a transcrição de uma sequência de DNA

traducao(seq) Função que devolve a tradução de uma sequência de DNA

valida(seq) Função que verifica se uma sequência de DNA é válida (devolve True ou False)

contar_bases(seq) Função que conta as bases de uma sequência e devolve um dicionário com a contagem

reading_frames(seq) Função que devolve uma lista com as reading frames

get_proteins(seq) Função que devolve a lista de todas as proteínas ordenadas por tamanho e por ordem alfabética para as do mesmo tamanho

Crie um módulo de testes que teste exaustivamente todas as funções providenciadas pelo seu módulo
Lembre-se que deve testar cada função em todos os casos possíveis
Não se esqueça das condições de fronteira
Crie a documentação do seu módulo e de todas as funções providenciadas
Bibliografia
Documenting Python code
Unit Testing Framework
Getting Started With Testing in Python
