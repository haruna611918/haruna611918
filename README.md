# タロットカードのデッキ
tarot_deck = {
    1: "The Magician - Creativity, willpower, manifestation, resourcefulness.",
    2: "The High Priestess - Intuition, subconscious, mystery, inner voice.",
    # 他のカードを追加
    # ...
    78: "The World - Completion, integration, accomplishment, travel.",
}

def draw_tarot_card():
    card_number = random.randint(1, 78)  # カードをランダムに選択
    return tarot_deck[card_number]  # カードの意味を返す

# カードを引く
drawn_card = draw_tarot_card()
print("Your tarot card for today is: ")
print(drawn_card)

--->
