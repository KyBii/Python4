# Tugas Python4
## 1. Perulangan For
### Source Code

```py
nama = "Abigail"

for item in nama:
    print(item, end=' ')
print("\n")
    
# perulangan list
print ("\n==========================")
num = [1,2,3]
for i in num:
    print(i)
print("\n")   

# perulangan in range
print ("\n=========================")
for i in range(3):  # list selalu dimulai dari nol
    print(i) 
```
### VS Code & Output
![A1](https://user-images.githubusercontent.com/93004722/140848349-cc7a5529-a7cc-4032-8ba3-7f451c16cbef.PNG)

## 2. List
### Source Code

```py
kata = ['sorry', 'bang', 'jago']
# mengambil urutan pertama dari list
print(kata[0])

# mengambil urutan terakhir dari list
print(kata[-1])

# mengambil berdasarkan range
print(kata[0:3])
```
### VS Code & Output
![A2](https://user-images.githubusercontent.com/93004722/140849207-068e1131-d987-416b-99ad-097eec2c570a.PNG)

## 3. List Method
### Source Code

```py
nomor = [7, 4, 2 ,1]
print(nomor)

nomor.append(69) #memasukkan objek pada list
print(nomor)

nomor.insert(0, 3) #memasukkan objek kedalam list pada index tertentu
print(nomor)

nomor.pop(1) #menghapus objek list pada index tertentu
print(nomor)

nomor.remove(69) #menghapus suatu objek didalam array
print(nomor)

nomor.sort() #mengurutkan item dalam list
print(nomor)
```
### VS Code & Output
![A3](https://user-images.githubusercontent.com/93004722/140849906-fc642467-7e7e-41c2-8fe4-76e063b28db3.PNG)

## 4. Menjumlahkan List
### Source Code

```py
nomor2 = [4, 6, 3, 5, 2]

nomor3 = 0

for nomor in nomor2:
    nomor3 = nomor3 + nomor

print(nomor3)
```
### VS Code & Output
![A4](https://user-images.githubusercontent.com/93004722/140851493-31cf1c3f-e89b-4356-8742-0555e56d4d33.PNG)

## 5. Mencari Angka Max
### Source Code

```py
nomor_nomor = [5,4,7,3,1]

nomormaks = max(nomor_nomor)
print(nomormaks)

#2
nomor_nomor.sort()
nomormaks = nomor_nomor[-1]
print(nomormaks)

#3
nomormaks = nomor_nomor[0]
for nomor in nomor_nomor:
    if nomor > nomormaks:
        nomormaks = nomor
print(nomormaks)
```
### VS Code & Output
![A5](https://user-images.githubusercontent.com/93004722/140852227-71727321-85ff-4220-a84e-9e97fa0d565c.PNG)

## 6. Tuple
### Source Code

```py
# Perbedaan dengan list, isi tuple tidak bisa diubah

angka = (6, 3, 7, 4, 5)
print(angka[2])
```
### VS Code & Output
![A6](https://user-images.githubusercontent.com/93004722/140853358-2e1289bc-e077-4d21-a96e-100aa17af743.PNG)

## 7. Unpack
### Source Code

```py
is_day = False
is_night = False

if is_day: 
    print("Selamat Siang") 
elif is_night: 
    print("Selamat Malam") 
else:
    print("Abigail Perkasa") 
```
### VS Code & Output
![R1](https://user-images.githubusercontent.com/93004722/140647175-b1ae7fc1-075a-4c75-a3dd-69faa3ce7bb5.PNG)

## 8. Dictionary
### Source Code

```py
grade = 4

if grade >= 8:
    print("Nilai kamu A")
elif grade >= 7:
    print("Nilai kamu B")
elif grade >= 6:
    print("Nilai kamu C")
else:
    print("Makanya belajar yang rajin")
```
### VS Code & Output
![R2](https://user-images.githubusercontent.com/93004722/140647557-33b34eb3-9080-40da-ba9f-67c72317c17c.PNG)
