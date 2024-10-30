import random
import matplotlib.pyplot as plt

# Все методы генерируют случайные числа от 1 до 6
def generate_random_numbers_method_1(n):
    return [random.randint(1, 6) for _ in range(n)]

def generate_random_numbers_with_comprehension(n):
    return [random.randrange(1, 7) for _ in range(n)]

def generate_random_numbers_with_for_loop(n):
    return [random.randint(1, 6) for _ in range(n)]

def generate_random_numbers_method_4(n):
    return [random.randint(1, 6) for _ in range(n)]

def generate_random_numbers_method_5(n):
    return [random.randint(1, 6) for _ in range(n)]

def generate_random_numbers_method_6(n):
    return [random.randint(1, 6) for _ in range(n)]

# Числа бросков
throw_counts = [100, 1000, 10000, 1000000]

# Генерация и вывод результатов для каждого метода
for count in throw_counts:
    print(f"\nРезультаты для {count} бросков:")

    results1 = generate_random_numbers_method_1(count)
    print(f"Метод 1 (1-6): {results1[:10]}...")

    results2 = generate_random_numbers_with_comprehension(count)
    print(f"Метод 2 (1-6): {results2[:10]}...")

    results3 = generate_random_numbers_with_for_loop(count)
    print(f"Метод 3 (1-6): {results3[:10]}...")

    results4 = generate_random_numbers_method_4(count)
    print(f"Метод 4 (1-6): {results4[:10]}...")

    results5 = generate_random_numbers_method_5(count)
    print(f"Метод 5 (1-6): {results5[:10]}...")

    results6 = generate_random_numbers_method_6(count)
    print(f"Метод 6 (1-6): {results6[:10]}...")
