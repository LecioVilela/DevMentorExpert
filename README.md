# DevMentorExpert
Controle de alunos da Mentoria .NET Expert

## Escopo
Cadastro: Nome, CPF, Celular, Email (Guid), Data de nascimento (Exemplo public class Pessoa)

Logradouro, Estado, Pais, CEP (public class endereco) *** Pensar futuramente ***

Preciso guardar data de início e defino fim em 6 meses ou 1 ano dependendo do ciclo, mas permito renovaç!ao (Talvez implementar uma notifação pro mentor, por exemplo faltando 15 dias para encerrar o periodo e então o mesmo entraria em contato para renovar ou nao o ciclo) (public class Mentoria)

Eventos tem data e horário de início e fim, além de link do Zoom

Ciclos da mentoria onde o Mentor acompanha as atividades ou PDI do seu mentorado (Pensar depois em um nome melhor para Ciclos)

Ciclo do mentorado onde ele participa em um periodo de 6 meses a 1 ano e tem sua quantidade de ciclos na mentoria (Pensar depois em um nome melhor para Ciclos)

## Entidades
Mentorado: Nome, CPF, Celular, Email, Aniversario
Ciclo: Inicio, Fim, Description
Eventos: data, horário de início e fim, link do Zoom
