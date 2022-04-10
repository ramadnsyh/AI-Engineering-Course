# Review Materi Tipe Data dan Fungsi

## Tipe Data

1.  Numeric:
    - merupakan tipe data yang merepresentasikan sebuah angka
    - Contoh:
        1. Integer: bilangan bulat contoh: 1, 2, 3
        2. Float: bilangan yang pake koma contoh: 1.5, 3.9
        3. Complex: bilangan riil dan imajiner contoh: 23 + 1j
2. Boolean
    - tipe data yang cuman terdiri dari 2 nilai yaitu `True` atau `False`
    - Dapat dibentuk dari beberapa cara:
        1. perbandingan: age < 30, age == 30, age != 10
3. String
    - tipe data untuk representasi data text
    - Contoh:
        1. "Hello my name is Rama"
        2. "symbol !@309?><"
        3. "123456"
4. List
    - Tipe data yang bisa berisi banyak data. Ciri2nya dia itu homogen.
    - Contoh:
        1. users = ["rama", "budi", "teguh"]
        2. score = [70, 60, 30, 100]
5. Tuple
    - Sama kayak list tapi dia gak bisa diubah nilai didalamnya.
    - Contoh:
        1. NIK = ("317407", "1231231", "12332")
6. Set
    - Untuk membuat nilai yang unique
    - Contoh:
        1. handphones = {"+623324", "+621233"}
7. Dict
    - Tipe data yang bisa berisi banyak data. Ciri2nya dia itu heterogen.
    - Contoh: 
        {
            "name": "rama",
            "age": 20,
            "address": {
                "city": "jakarta",
                "RT": 1
            },
            "hobbies": ["swimiming", "running"]
        }
        
## Function

Tujuan membungkus kode kita agar bisa digunakan berkali2. Contoh fungsi mencari rata2.
Komponent:
    1. Nama fungsi: `def <nama_fungsi>`
    2. Parameter / Input: `def <nama_fungsi>(<input1>, <input2>, ...):`
    3. Output: `return <nilai akhir / keluaran dari fungsi tersebut>`
