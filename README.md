# projeto-de-contribui-o-com-portugol
portugol
programa {
funcao inicio() {
real nota1, nota2, nota3, faltas, media
escreva("Digite a primeira nota:")
leia(nota1)
escreva("Digite a segunda nota:")
leia(nota2)
escreva("Digite a terceira nota:")
leia(nota3)
escreva("Informe a quantidade de faltas do aluno:")
leia(faltas)
se (faltas>18)
{
escreva("O aluno está reprovado por faltas!")
}
senao
{
media = (nota1+nota2+nota3)/3
se (media>=7)
{
escreva("O aluno está APROVADO!")
escreva("Sua nota final é: ", media)
}
senao
{
se (media<7 e media>=5)
{
escreva("O aluno está em recuperação!\n")
escreva("Sua nota final é: ", media)
}
senao
{
escreva("O aluno está REPROVADO!\n")
escreva("Sua nota final é: ", media)
}
}
}
}
}
