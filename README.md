#Catalog items

#Assigning lovely_loveseat_description variable

lovely_loveseat_description = """Lovely Loveseat. Tufted polyester blend on wood. 32 inches high x 40 inches wide x 30 inches deep. Red or white."""

#Assigning lovely_loveseat_price variable

lovely_loveseat_price = 254.00

#Assigning stylish_settee_description variable

stylish_settee_description = """Stylish Settee. Faux leather on birch. 29.50 inches high x 54.75 inches wide x 28 inches deep. Black."""

#Assigning stylish_settee_price variable

stylish_settee_price = 180.50

#Assiigning luxurious_lamp_description variable

luxurious_lamp_description = "Luxurious Lamp. Glass and iron. 36 inches tall. Brown with cream shade."

#Assigning luxurious_lamp_price variable

luxurious_lamp_price = 52.15

#Assigning sales_tax variable

sales_tax = .088

#Customer purchase

#Assigning customer_one_total variable

customer_one_total = 0

#Assigning customer_one_itemization variable

customer_one_itemization = ""

#Adding first customer purchase to customer_one_total variable

customer_one_total += lovely_loveseat_price

#Adding description of lovely loveseat to customer_one_itemization variable

customer_one_itemization += lovely_loveseat_description

#Adding price of luxurious lamp to customer one's total

customer_one_total += luxurious_lamp_price

#Adding description of luxurious lamp to customer itemization

customer_one_itemization += luxurious_lamp_description

#Calculations

#Assigning customer_one_tax variable

customer_one_tax = customer_one_total * sales_tax

#Total amount to be paid by customer one

customer_one_total += customer_one_tax

#Printing receipts

#Printing the customer's receipt

print("Customer One Items:")

print(customer_one_itemization)

print("Customer One Total:")

print("$""{:.2f}".format(customer_one_total))
