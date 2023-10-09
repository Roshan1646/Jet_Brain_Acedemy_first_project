# Jet_Brain_Acedemy_first_project

# total earning of each item

Bubblegum_tot = int(202)
Toffee_tot = int(118)
Ice_cream_tot = int(2250)
Milk_chocolate = int(1680)
Doughnut = int(1075)
Pancake_tot = int(80)

# print the summary of the total earning

print("Earned amount:")
print(f"Bubblegum: ${Bubblegum_tot}")
print(f"Toffee: ${Toffee_tot}")
print(f"Ice cream: ${Ice_cream_tot}")
print(f"Milk chocolate: ${Milk_chocolate}")
print(f"Doughnut: ${Doughnut}")
print(f"Pancake: ${Pancake_tot}")

# print the total income

income = float(Bubblegum_tot+Toffee_tot+Ice_cream_tot+Milk_chocolate+Doughnut+Pancake_tot)
print(f"Income: ${income}")

Staff_expense = int(input("Staff expenses:"))


other_expenses = int(input("Other expenses:"))

# Net profit cal
net_income = int(income - (Staff_expense + other_expenses))


print("Net income: $",  net_income)

