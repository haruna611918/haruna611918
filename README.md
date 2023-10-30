- 👋 Hi, I’m @haruna611918
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
haruna611918/haruna611918 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take
a look at your changes.
import random

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
