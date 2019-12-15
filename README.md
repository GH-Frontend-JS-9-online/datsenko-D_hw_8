Homework 8

3. Practice task: 
    - Create tamagochi (make sure you go over https://learn.javascript.ru/introduction-browser-events first):
        + Stats:
            + food
            + clean
            + happiness
        - Actions:
            + eat: +30 food ; -20 clean
            + wash: +40 clean ; -20 hapiness
            + run: +15 happiness ; -10 food
        - Rules:
            + all stats should decrease each 5 second
            + all stats should start with random points within 50-100 range
            - all stats should be displayed as bars
            + actions should be displayed as buttons, each action has separate button
            + player should click on action buttons to increase stat
            - player will lose if one of stats got 0
            + player will see time amount how long Tamagotchi lived
            - player can restart if lose
            - player should select a Tamagotchi type on start
        - Two types of Tamagotchi:
            - Lazy pug (hard level)
                + stats decrease 5 points per 5 second
                - max points each stat is 70
            - Fluffy kitty (easy level)
                - stats decrease 3 points per 5 second
                - max points each stat is 100
