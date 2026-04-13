import random
secret = random.randint(1 , 100)
essai = 0
print(" J'ai choisi un nombre entre 1 et 100 , devnine le nb .")

while True : 

 R = int  ( input ( " Votre Choix : ")) 
 essai += 1 

 if R == secret  : 
   print( f" Bravo ! Tu a trouver en {essai}  ")
   break 
 elif  R < secret  : 
    print ( " trop petit !")
 elif  R   > secret  : 
    print ( " Trop grand ")
