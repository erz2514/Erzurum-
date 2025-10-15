"""
Python String Formatting - W3Schools Örnekleri

Sayfa: https://www.w3schools.com/python/python_string_formatting.asp
"""

# === F-Strings Örnekleri ===
print("=== F-Strings Örnekleri ===")

name = "Alice"
print(f"Hello, {name}!")  # Basit kullanım

price = 49
print(f"The price is {price * 1.2:.2f} dollars")  # İfade ve formatlama

def greet(name):
    return f"Hello, {name}!"
print(f"{greet('Bob')}")  # Fonksiyon kullanımı

# === format() Metodu Örnekleri ===
print("\n=== format() Metodu Örnekleri ===")

# Pozisyonel formatlama
print("Hello, {}!".format("Charlie"))

# Anahtar kelime formatlama
print("The price is {price:.2f} dollars".format(price=49))

# Sözlük kullanımı
data = {"name": "David", "age": 30}
print("Name: {name}, Age: {age}".format(**data))
