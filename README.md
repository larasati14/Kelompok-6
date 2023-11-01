# Pelanggan masuk dan diberi sambutan yang ramah
print("Selamat datang di Pizza Hut, ada yang bisa kami bantu?")

# Menginformasikan kepada pelanggan terkait menu yang tersedia 
print("""
Ini menu yang tersedia hari ini, silahkan pilih menu yang ada mau.
  Menu Pizza:
  [1] Frankfurter
  [2] Meat Monsta
  [3] Super Supreme
  [4] Super Supreme Chicken
  """)
Pizza = int(input("Pizza yang ingin di pesan: "))

# Ukuran pizza yang diinginkan
print ("""
Selanjutnya silahkan pilih ukuran pizza yang anda mau.
  Pilih ukuran:
  [A] Personal
  [B] Regular
  [C] Large
  """)
Ukuran = (input("Ukuran pizza yang anda pilih: "))

# Pilih pinggiran pizza
print("""
Lalu silahkan pilih pinggiran pizza anda
  Crust:
  [A] Pan
  [B] StuffedCrust Pizza
  [C] StuffedCrust Sausage
  [D] Cheese Bites
  """)
Crust = (input("Crust pizza yang anda pilih "))

# Pilihan opsional untuk extra cheese
print("""Apakah anda ingin extra cheese atau tidak?
      [A] Dengan Extra Cheese
      [B] Tanpa Extra Cheese
      """)
Extra_cheese = input ("Apakah anda ingin extra cheese? Y/N")

# Code perintah untuk menjalankan pesanan secara otomatis
if Pizza in range (1, 4):

    # Harga Ukuran
    if Ukuran == "Personal"
        harga_ukuran = 43636
    elif Ukuran == "Regular"
        harga_ukuran = 100909
    else:
        harga_ukuran = 132727

    # Harga Crust 
    if Crust == "Pan":
            harga_crust = 0
    elif Crust == "StuffedCrust cheese":
            harga_crust = 11819
    elif Crust == "StuffedCrust Sausage":
            harga_crust = 9091
    else: 
        harga_crust = 136371

    # Harga Extra Cheese
    if Extra_cheese == "Y":
        harga_extra_cheese = 13000
    else:
        harga_extra_cheese = 0

else:
    print("salah")
