name = input("Salut! Quel est ton nom? ")
print("Salut " + name + "!")

play = None
while play not in ("oui", "non"):
    play = input("Souhaite-tu participer au quiz de 5 questions? ").lower()
    if play == "oui":
        print("Magnifique! C'est parti!")
    elif play == "non":
        print("Dommage... Peut-être une prochaine fois!")
        quit()
    else:
        print("Peux-tu répondre par \"oui\" ou par \"non\" s'il te plaît? ")
        
points = 0
answer = input("Question n°1: Quel animal ne peut pas sauter? ").lower()
if "léphant" in answer:
    print("Bonne réponse! Tu gagnes 1 point! ")
    print("Pas besoin de sauter quand tu pèse de 5 à 8 tonnes. Il suffit de tout écraser!")
    points += 1
else:
    print("Oh non! Mauvaise réponse!")
    
answer = input("Question n°2: Quel est le résultat du calcul mathématique 3²? ")
if "9" in answer:
    print("Bonne réponse! Tu gagnes 1 point! ")
    print("Comme ça, tout le monde a au moins un point! Enfin, peut-être...")
    points += 1
else:
    print("Oh non! Mauvaise réponse!")
    
answer = input("Question n°3: Quel est l'organe le plus grand du corps humain? ").lower()
if "peau" in answer:
    print("Bonne réponse! Tu gagnes 1 point! ")
    print("Et ouais! Tu n'es pas tombé dans le piège en répondant \"intestin grêle \" qui peut mesurer jusqu'à 6 mètres")
    points += 1
else:
    print("Oh non! Mauvaise réponse!")
    
answer = input("Question n°4: Quelle est la capitale de l'Australie? ").lower()
if "canberra" in answer:
    print("Bonne réponse! Tu gagnes 1 point! ")
    print("Quoi? Ce n'est pas Melbourne? Ni Sydney? Je tombe des nu...")
    points += 1
else:
    print("Oh non! Mauvaise réponse!")
    
answer = input("Question n°5: Quel fruit est l'ingrédient principal de la sauce bolognaise? ")
if "tomate" in answer:
    print("Bonne réponse! Tu gagnes 1 point! ")
    print("Tout ça m'a donné faim!")
    points += 1
else:
    print("Oh non! Mauvaise réponse!")
    
if points == 1:
    print("Tu as 1 point sur 5!")
else:
    print("Tu as " + str(points) + " points sur 5!")

totalPoints = {
    0 : "Pardon, je tâcherais de diminuer la difficulté la prochaine fois.",
    1 : "L'honneur est sauf!",
    2 : "Tu as presque atteint la moyenne! Encore un petit effort!", 
    3 : "Bien joué, tu as dépassé la moyenne!",
    4 : "Très bon résultat! Tu as presque atteint le score parfait!",
    5 : "Score parfait atteint! Le monde n'a plus aucun secrets pour toi!"
}
print(totalPoints[points])