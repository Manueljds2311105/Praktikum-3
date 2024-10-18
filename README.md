# Praktikum 3

NAMA: MANUEL JOHANSEN DOLOK SARIBU

NIM: 312410493

DOSEN PENGAMPU: Agung Nugroho, S.Kom., M.Kom., 

MATA PELAJARAN: BAHASA PEMOGRAMAN 

# Menentukan Bilangan Terbesar

## BUAT KODE PROGRAM PYTHON DARI FLOWCHART SEBELUMNYA:

```python
# Initialize max number to None (to handle the first input)
max_number = None

while True:
    # Ask for user input
    n = int(input("Enter a number (0 to stop): "))
    
    # If the input is 0, exit the loop
    if n == 0:
        break
    
    # If max_number is None or n is greater than max_number, update max_number
    if max_number is None or n > max_number:
        max_number = n

# Output the result
if max_number is not None:
    print("The largest number entered is:", max_number)
else:
    print("No numbers were entered.")
```

## FOTO FLOWCHART SEBELUMNYA

![foto](https://github.com/Manueljds2311105/Praktikum-3/blob/fe52ba3a0d99559ab9ffa5cfa38de3701d30bca1/Flowchart%202.png?raw=true)

## FOTO HASIL EKSEKUSI KODE PROGRAM PYTHON

![foto](https://github.com/Manueljds2311105/Praktikum-3/blob/d4b890cb2d01ebbcc122dfbba2cb4421cd78cdb7/Hasil%20Eksekusi%20Kode%20Python.png?raw=true)
