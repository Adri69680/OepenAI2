print("IA : Salut ! Pose une question (écris 'stop' pour quitter)")

while True:
    q = input("Toi : ").lower()

    if q == "stop":
        print("IA : Au revoir")
        break

    elif "bonjour" in q:
        print("IA : Bonjour !")

    elif "comment tu t appelles" in q or "qui es tu" in q:
        print("IA : Je suis une petite IA simple.")

    elif "ca va" in q:
        print("IA : Oui, ca va bien. Merci !")

    elif "quoi" in q or "pourquoi" in q or "comment" in q:
        print("IA : Bonne question. Explique un peu plus.")

    else:
        print("IA : D'accord. Continue.")
