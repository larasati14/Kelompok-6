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
Extra_cheese = input ("Apakah anda ingin extra cheese? Y/N")

