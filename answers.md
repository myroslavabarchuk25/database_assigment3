1. What is the difference between a function and a procedure in PostgreSQL?
   Функція завжи щось повертає, а процедура не обов'язково.
   Функція викликаэться в select, where, join, а процедура лише через call.
2. Can a trigger be executed manually? Why or why not?
   Ні бо суть тригеру у тому, що він викликається автоматично на те що ти вкажеш.
   Якщо цього не сталось то тригер не спрацює і не виконається
3. What are the advantages and disadvantages of storing business logic inside the database?
   Переваги:
   код і дані в одному місці 
   один раз написав і викликаєш коли треба логіка праццює однаково для всього
   Недоліки:
   менше хороших спеціалістів
   не буде працювати на різних IDE
