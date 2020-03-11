import random

def choice_percent(* n):
   list_numbers = []
   list_percents = []
   list_choice = []
   if (len(n) % 2) == 0:
      c = 0
      contagem = int(len(n) / 2)
      for i in range(0, contagem):
         list_numbers.append(n[c])
         c += 1
         list_percents.append(n[c])
         c += 1

      soma = 0
      for i in list_percents:
         try:
            soma = soma + i
         except:
            choice = ('Parâmetros: "item, porcentagem, item, porcentagem" \nA soma das porcentagem tem que ser exatamente = 100')
            break
         
      if soma == 100:
         c = 0
         for i in list_percents:
            i * 100
            while i > 0:
               list_choice.append(list_numbers[c])
               i -= 1
            c += 1
         choice = random.choice(list_choice)
      else:
         choice = ('Parâmetros: "item, porcentagem, item, porcentagem" \nA soma das porcentagem tem que ser exatamente = 100')
      
   else:
      choice = ('Parâmetros: "item, porcentagem, item, porcentagem" \nA soma das porcentagem tem que ser exatamente = 100')
      
      
   return choice


#exemplo de como utilizar
for i in range(0, 1000):
    n = choice_percent('item 1 com 0,01% de chance de ser sorteado', 0.01, 'item 2 com 99.99%', 99.99)
    print('tentativa numero', i, '|', n)
    if n == 'item 1 com 0,01% de chance de ser sorteado':
        exit()










    
