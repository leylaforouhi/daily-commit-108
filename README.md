def find_common_elements(list1, list):
    return list(set(list1) & set(list2))

if __name__ == "__main__":
    first = [1, 2, 3, 4, 5]
    second = [4, 5, 6, 7, 8]

    print(f"First list: {first}")
    print(f"Second list: {second}")
    print(f"Common elements: {find_common_elements(first, second)}")
