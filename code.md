## Код для нахождения среднего арифметического массива

numbers = [2, 5, 13, 7, 6, 4]
size = len(numbers)
suma = 0
avg = 0
index = 0
if index < size:
    suma = suma + numbers[index]
    index +=1
avg = suma / size
print (avg)