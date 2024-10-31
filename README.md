# pytton-project
#menu_project


  print('Welcome to our Hotel.')
print("Here's the many :")

menu = {
  'DOSA':60,
  'VADAPAU':30,
  'MANCHURIAN':120,
  'PAU-BAJI':90,}
print('\fDOSA:60,\n VADAPAU:30,\n MANCHURIAN:120,\n PAU-BAJI:90')

order_total=0   

print("What is your first order = ")
order1 = input()
order_total += menu[order1]

if order1 in menu:
  print("orded")
else:
  print("not in menu, plese order somethig else")

print("Do you want to order anything else(0=YES/1=NO) = ")
order2 = input()

if 0:
  print("What is your second  order = ")
  order3 = input()
  order_total += menu[order3]
else:
   print("Thank you for ordering.")

print("I HOPE YOU ENJOY")

print(f"Total amount = {order_total}")
