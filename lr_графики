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

    # Подсчет процентов
    def calculate_percentages(results, count):
        counts = [results.count(i) for i in range(1, 7)]
        percentages = [(c / count) * 100 for c in counts]
        return percentages

    percentages1 = calculate_percentages(results1, count)
    percentages2 = calculate_percentages(results2, count)
    percentages3 = calculate_percentages(results3, count)
    percentages4 = calculate_percentages(results4, count)
    percentages5 = calculate_percentages(results5, count)
    percentages6 = calculate_percentages(results6, count)

    # Построение графиков
    plt.figure(figsize=(20, 10))

    # График для метода 1
    plt.subplot(2, 3, 1)
    plt.bar(range(1, 7), percentages1, alpha=0.7, color='blue', edgecolor='black')
    plt.title(f'Метод 1: {count} бросков')
    plt.xlabel('Значение')
    plt.ylabel('Процент выпадения')

    # График для метода 2
    plt.subplot(2, 3, 2)
    plt.bar(range(1, 7), percentages2, alpha=0.7, color='green', edgecolor='black')
    plt.title(f'Метод 2: {count} бросков')
    plt.xlabel('Значение')
    plt.ylabel('Процент выпадения')

    # График для метода 3
    plt.subplot(2, 3, 3)
    plt.bar(range(1, 7), percentages3, alpha=0.7, color='orange', edgecolor='black')
    plt.title(f'Метод 3: {count} бросков')
    plt.xlabel('Значение')
    plt.ylabel('Процент выпадения')

    # График для метода 4
    plt.subplot(2, 3, 4)
    plt.bar(range(1, 7), percentages4, alpha=0.7, color='purple', edgecolor='black')
    plt.title(f'Метод 4: {count} бросков')
    plt.xlabel('Значение')
    plt.ylabel('Процент выпадения')

    # График для метода 5
    plt.subplot(2, 3, 5)
    plt.bar(range(1, 7), percentages5, alpha=0.7, color='red', edgecolor='black')
    plt.title(f'Метод 5: {count} бросков')
    plt.xlabel('Значение')
    plt.ylabel('Процент выпадения')

    # График для метода 6
    plt.subplot(2, 3, 6)
    plt.bar(range(1, 7), percentages6, alpha=0.7, color='cyan', edgecolor='black')
    plt.title(f'Метод 6: {count} бросков')
    plt.xlabel('Значение')
    plt.ylabel('Процент выпадения')

    plt.tight_layout()
    plt.show()
