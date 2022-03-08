x=[[1,'a',['cat'],2],[[[3]],'dog'],4,5]

new_list = []
def flatten(data): 
  for eleman in data: 
    if type(eleman) == list: 
      duzlestir(eleman) 
    else: 
      new_list.append(eleman) 
      flatten(x)  
    print(new_list)



y=[[1, 2], [3, 4], [5, 6, 7]] 
new=list() 
for i in sorted(y,reverse=True): 
  new.append(sorted(i, reverse=True)) 
  print(new)
