# Условные операторы    


Следующее что важно узнать - условия (в оригинале if statements). Понятно, что та или иная операция происходит в зависимости от многих факторов, например банкомат выдаст тебе деньги если были соблюдены несколько условий: банкомат смог прочитать твою банковскую карту, ты ввел правильный ПИН код, у тебя есть сумма на счету, и так далее. Так как компьютер всего лишь исполняет то, что ты скажешь ему сделать, логично что в языках программирования есть условные инструкции. В Python они выглядят следующим образом:   

<iframe height="400px" width="100%" src="https://repl.it/@SakenMukanov/WhichAggressiveDatum?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>


Заметка - в языке Python нужно обязательно ставить табуляцию как в примере выше, табуляция ставится нажатием кнопки tab.    
    
<iframe width="100%" height="315" src="https://www.youtube.com/embed/EggJRTzid1M" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>    
   

В первый **if** передается **условие** которое проверяется на правдивость (например запрашиваемая сумма < суммы на банковском счету).  
Так как любое условие может быть или правдой или неправдой, мы можем знать какой будет результат, и выполнять соответствующие операции.    
Если первое условие в if оказался правдой, **print('Число положительное')** выполнится, и программа не будет проверять что находится в  **elif** и **else**, так как первый if выполнился. 
Если первое условие в if оказалось неправдой, то программа перейдет к следующему условию elif. Если следующий elif оказался правдой, то выполнятся его действия, в данном случае **print('Число отрицательное')**. Если все if, elif окажутся неправдой, выполнится только **else**, если его нет, ничего не выполнится.


В if и elif можно передавать несколько условий и объединять их:
- if (условие1 **and** условие2) - будет правдой только если оба условия правдивы   
- if (условие1 **or** условие2) - будет правдой если хотя бы одно условие правдиво    

Таким образом можно делать комплексные условия.   

Для большего понимания посмотри и <a href="https://pythontutor.ru/lessons/ifelse/" target="_blank">попрактикуйся здесь</a>.

# Задача для практики:
Тебе нужно спросить у пользователя его возраст, и вывести на экран совершеннолетний ли он или нет.
Пример:
"Привет, сколько тебе лет?"    
"17"   
"Тебе еще нет 18"   

"Привет, сколько тебе лет?"    
"19"   
"Ты совершеннолетний"  


