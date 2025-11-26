# Word-filter
# laboratory work in information technology
words = []

for i in range(5):
    word = input("Введіть слово: ")

if len(word) == 0:
        continue  # якщо ввели порожній рядок — пропускаємо

if word[0].islower():  # перевіряємо перший символ
        continue

words.append(word)

print("Слова з великої літери:")
for w in words:
    print(w)
