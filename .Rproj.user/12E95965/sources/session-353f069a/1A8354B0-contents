# Os objetos precisam ser criados!

# Texto deve ser inserido com aspas "olá" ou 'olá'
hello = "olá"

# Números são atribuidos sem aspas
nota = 7

# A função c() combina elementos dentro de um vetor
hello = c('olá', 'Papai Cris', "Adulto Ney")
nota = c(7, 10, 9)
hello
nota

# Para acessar o conteúdo de alguma posição anterior do vetor

hello[2]
hello[2:3]
hello[c(1,3)]

# Para criar uma planilha (data.frame), basta usar a função data.frame

dados = data.frame(hello,nota)

# Como exportar uma base do R?

# Exportando como .csv
write.csv(dados, "Aula01.csv", row.names = FALSE)

# Como no Brasil, utiliza-se a vírgula como separador de decimal, existe um formato brazuca.
write.csv2(dados, "Aula01_br.csv", row.names = FALSE)

library(writexl)
write_xlsx(dados, 'aula01.xlsx')

x = c(1, 2, 3, 4, 5)
y <- c(6, 7, 8, 9, 10)
x -> z

class(dados)

# Algumas funções só pode ser usadas para determinadas classes.
dim(dados)

x = as.array(x)
dim(x)

hello = as.numeric(hello)
# NA = not avaliable

nota = as.character(nota)
nota = as.numeric(nota)

# Classe Logical
h = c("e", "s", "p", "m")  # usar aspas com textos
i = h == "p"
i
which(i)

# Vamos falar da classe factor na semana que vem.