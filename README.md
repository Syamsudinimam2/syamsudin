os.system ('clear')

Lmenu = ("""▗▄▄▄▖▗▄▄▄▖  ▖
▝▀█▀▘▝▀█▀▘ ▄▙▖
  █    █  ▐▛▛▘
  █    █  ▝█▙▖
  █    █    ▛█
  █    █  ▐▄▙█
  ▀    ▀   ▀▛▘
            ▘""")


Pmenu = ("""
MULAI
FAQ
SUPORT
EDIT GAME""")



                                                                                                                                     #warna
M = "\x1b[1;91m"

logo = ("""\x1b[1;91m╺┳╸╺┳╸┏━┓
 \x1b[1;97m┃\x1b[1;97m  ┃ ┗━┓
 ╹  ╹ ┗━┛""")

print (logo,M)
print ('──────────────────────────────────────────────────────────────')
print ('\x1b[1;95m😈PILIHLAH JAWABAN  dibawah ⬇ ini dengan BENAR!!!\n',M)
print ('──────────────────────────────────────────────────────────────')
soal1 = ("""\x1b[1;97m1. Apa nama wadah untuk menanam tanaman hias... \x1b[1;91m?\n
\x1b[1;94mA.\x1b[1;97mMangkok
\x1b[1;94mB.\x1b[1;97mJamban
\x1b[1;94mC.\x1b[1;97mPot""")

print (soal1)
soal1 = input ('\n\x1b[1;93mPilih:\x1b[1;94m ')

if soal1 == "c" or soal1 == "pot":time.sleep(1) , print ('\x1b[1;92m✔ ') , time.sleep(1) , print ('\x1b[1;94mBener Anjir😆')

else :print ('\x1b[1;31mSalah Tood🙄')
