## Dynamic programming solution to the following problem

You are an aspiring fighter, planning to hone your skills in the famous Dynamic Arena. This arena does not maintain a consistent structure. Instead, the arena’s floors rise and fall dynamically throughout the day, making the climb more unpredictable and dangerous.
You want to strategically plan your fighting episodes. An Episode is a sequence of two actions: arena entry then winning in combat. You can engage in multiple fighting episodes, but you cannot engage in more than one combat in the same episode. In other words, once you fight in combat, you need to start a new episode of entry then combat. However, there is a catch, you cannot engage in two episodes consecutively, you need to wait for at least one arena movement to pass. Given that you have been training really well, you know that once you chose to fight, you will win.
You need to choose the right time to enter the arena first, then choose the right time to engage in combat. In order to start an episode, you will have to pay an entry fee and when you win in combat you will gain a reward. The entry fee and the reward are each equal to the floor the arena is in when you make your moves. Your goal is to maximize the rewards you get while in the Dynamic Arena.

                                   [1,7,5,3,6,4,5,8]
                                   
The largest number of floors that a fighter can climb is (7 − 1) + (6 − 3) + (8 − 5) = 12.
• Floor 1: Enter the arena.
• Floor 7: Fight to get the reward of floor 7. • Floor 5: Do nothing.
• Floor 3: Enter the arena.
• Floor 6: Fight to get the reward of floor 6. • Floor 4: Do nothing.
• Floor 5: Enter the arena.
• Floor 8: Fight to get the reward of floor 8.

Your algorithm should not run in an exponential time.
