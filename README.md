meme_dict = {
    "CRINGE": "Algo vergonhoso ou constrangedor",
    "STALKEAR": "Investigar a vida de alguém online",
    "VDD": "Abreviação da palavra 'verdade'",
    "BISCOITAR": "Postar algo apenas para chamar atenção",
    "HATER": "Pessoa que está constantemente criticando os outros",
    "VLW": "Abreviação da palavra 'valeu'"
}

word = input("Digite uma palavra moderna que você não entende: ")

if word in meme_dict.keys():
    print(meme_dict[word])
else:
    print("Desculpe, não conheço essa palavra.")
