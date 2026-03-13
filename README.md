# Simple-Bubble-sort-program-
Data structure practical program 
# Bubble Sort in Python

def bubble_sort(arr):
    n = len(arr)
    for i in range(n):
        for j in range(0, n - i - 1):
            if arr[j] > arr[j + 1]:
                # Swap if element is greater than next
                arr[j], arr[j + 1] = arr[j + 1], arr[j]

# Example usage
arr = [64, 34, 25, 12, 22, 11, 90]
print("Original array:", arr)

bubble_sort(arr)
print("Sorted array:", arr)

output:
Original array: [64, 34, 25, 12, 22, 11, 90]
Sorted array: [11, 12, 22, 25, 34, 64, 90]
