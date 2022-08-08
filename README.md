#10958775(MAXWELL ODOOM ANANE)
prime_number = []

for number in range(1,1000):
  if number > 1:
    for value in range(2, number):
      if (number % value) == 0:
        break
    else:
      #Add the prime numbers to the list
      prime_number.append(number)
print(prime_number)

#Print the sum of the prime numbers in the list.
total = sum(prime_number)
print(total)
