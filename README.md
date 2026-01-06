# random-guess
import random
target_num, guess_num = random.randint(1, 10), 0
while target_num != guess_num:
guess_num = int(input(&#39;Guess a number between 1 and 10 until you get it right : &#39;))
print(&#39;Well guessed!&#39;)
