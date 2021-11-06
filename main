print("You wake up in a strange room with 9 people who had their hands cuffed with guardsmen surrounding the room and one labcoat guy asking everyone their names")
name = input("The guy asks: What is your name kid? ")
age = int(input("Hah, what a strange name. How old are you? "))

health = 100

if age >= 16:
    print("heh, I guess you are old enough")
    print("A man wearing a black suit enters the room: I suppose you don't understand what is happening. You have been brought here to play a survival game on our island for our guests entertainment. The one who wins gets their freedom, and the rest.... You know what happens when you lose or don't play don't you? ")
    print("One of the handcuffed guy shouts: I don't want to play your stupid game, let me out!! ")
    print(" A bunch of guardsmen hold his hands and drag him towards a shady room... ")

    player_action1 = input("Do you yell at the guards to stop them or try to escape (yell/escape)? ").lower()
    if player_action1 == "yell":
        print("The guy in the suit says: Ohh, looks like we have someone who has some guts here. Alright boys, let him go. I will allow him to play")
        print("Don't you disappoint me now kiddo!!")
        print("The man shouts: Remember, this is a game of life and death. So either you live, or you...hahaha you know how it goes")
        print("AND NOW, DESCEND INTO MADNESS")

        print(" One of the guards then leads you through a passage and you finally enter the island.")
        print("You are staring with", health, "health")
        print("There are two paths... Left or Right!")
        
        left_or_right = input(" which way should you go? (left/right)? ")
        if left_or_right == "left":
            print("Nice, you follow the path and reach a lake...") 
            ans = input(" Do you swim across or go around via a dark forest (across/around)? ")

            if ans == "around":
                print("You went around the lake towards the forest. It was still evening time but once you entered the forest, it became as dark as the night sky. You kept walking and reached the other side of the lake.")
            elif ans == "across":
                print("You jump into the lake and start swimming. You managed to get across, but were bitten by a fish and lost 20 health.")
                health -= 20
    

            print("You start walking along the bumpy path, you notice a spooky house along the way.")
            ans = input(" Do you visit the house or keep walking? (house/walk)? ").lower()
            if ans == "house":
                print("You go to the house and see a bow and a rusty sword stashed in a box")

                sword_or_bow = input("Do you pick the sword or the bow (sword/bow)? ").lower()
                if sword_or_bow == "sword":
                    print("As you pull out the sword, an angry snake sitting behind the box bites you.")
                    print("You quickly shake it off and hit it with your sword")
                
                    print("you lost 50 health")
                    health -= 40
                else:
                    print("As you pull out the bow, an angry snake sitting behind the box bites you")
                    print("You shake it off but you realize you need arrows to hit the snake. You get bitten again and lose 80 health")
                    health -= 80


                if health <= 0:
                    print("You now have 0 health and you lost the game...")
                else:
                    print("You have survived... You win!")

            else:
                print("You accidentally fell in a pit and lost...")


        else:
            print("You accidentally fell down in a pit and lost...")

    else:
        print("A bunch of guardsmen grab your arm and drag you to a different room... Game Over ")
else:
    print("You are still a greenhorn kid, I guess we need to send you back home...")

