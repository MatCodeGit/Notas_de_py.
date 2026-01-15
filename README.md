# Notas_de_py.
anotações e codigos de python
s1 = 'Alura'

s1 = 'Alura'
s2 = "Alura"
print(type(s1), type(s2))

texto = 'Matheus Ferreira Feliciano da Silva'

print(texto)

texto.upper()

texto.lower()

texto.strip()

texto.replace('m','M')

texto = texto.strip()

print(texto)

nome = input('Escreva seu Nome: ')

ano_entrada = input('Escreva o ano de ingresso do(a) estudante: ')

type(ano_entrada)

ano_entrada = int(input('Escreva o ano de ingresso do(a) estudante: '))

print(ano_entrada)

type(ano_entrada)

Nota_entrada = float(input('Digite a nota do teste do ingresso: '))

nota_entrada = float(input('Digite a nota do teste de ingresso: '))
print(f'')

nota_entrada = float(input('Digite a nota do teste de ingresso: '))
print(f'Ano de entrada {ano_entrada}')

nota_entrada = float(input('Digite a nota do teste do ingresso: '))
print(f'Ano de entrada {ano_entrada} - nota do teste de ingresso {nota_entrada}')

nome = "Lucas Silva"
idade = 20
print(f"O nome do aluno é {nome} e sua idade é {idade} anos.")

nome_aluno = 'Fabricio Daniel'
print('Nome do aluno: %s' %(nome_aluno))

nome_aluno = 'Lara Danilla'
idade_aluno = 19
media_aluno = 8.45

print('Nome do aluno é %s, ele tem %d anos e sua média é %.2f.' %(nome_aluno, idade_aluno, media_aluno))

nome_aluno = 'Fabiano Amaral'
idade_aluno = 22
media_aluno = 8.0

print('Nome do aluno é {}, ele tem {} anos e sua media é {}.' .format(nome_aluno, idade_aluno, media_aluno))

