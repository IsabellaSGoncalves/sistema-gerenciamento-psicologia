
📌 Issue 02 - Tela PaginaCalendario.js

## Calendário em Inglês

## 🧩 Contexto

Durante a visualização da agenda há partes em inglês como Date, Time, Event e no caso de não possuir agendamentos o erro: "There are no events in this range".
Ou também se o agendamento persistir o dia todo, está no Time, como: "all day"

## 🔍 Passos para reproduzir 

Ter agendamentos e os verificá-los na parte de Agenda que está ao lado de Semana, certas mensagens estão em inglês.

## ✅ Resultado esperado

Que as mensagens sejam em português para melhor entendimento.

## 💡 Sugestão 

No calendário( Drag and Drop calendar) adicione:

messages={{
    date: 'Data', 
    time: 'Hora', 
    event: 'Agendamento', 
    allDay: 'Dia inteiro', 
    noEventsInRange: 'Não há eventos para este período',
    showMore: function showMore(total) {
        return '+' + total + ' agendamentos';
    } 
}}

Para personalizar as mensagens quando não há agendamentos na agenda, os campos na agenda e quando há mais de um agendamento. 
