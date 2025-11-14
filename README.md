# GAME_PROGRAM-EX--2

# Aim:
To Create a player movement using pawn, collectible, player health and score.

# Procedure To Create and Destroy the coin:
1.Create a new project in Unreal Engine and choose a template that suits your needs.

2.Add a new actor to the level and call it "Coin"

3.Create a new blueprint based on the Coin actor by selecting it in the Content Browser and choosing "Create Blueprint".

4.Open the Coin blueprint and add a static mesh component to represent the coin. You can import a 3D model or use one of the default shapes provided by Unreal Engine.

5.Add a collision component to the Coin blueprint so that the player can interact with it. Choose a simple collision shape like a sphere or a box.

6.Add a collision component to the Coin blueprint so that the player can interact with it. Choose a simple collision shape like a sphere or a box.

7.Create a new blueprint based on the player character by selecting it in the Content Browser and choosing "Create Blueprint".

8.Open the player blueprint and add a collision component to represent the player's interaction with the coins.

9.Add an event to the player blueprint that getstriggered when the player collides with a coin. Use a collision event and check if the collided actor is a coin.

10.If the collided actor is a coin, check if it has already been collected. If not, set its IsCollected variable to true and add its value to a score variable in the player blueprint.

11.Remove the coin from the level by calling its Destroy function.

12.Add several instances of the Coin actor to the level and adjust their positions so that they are spread out and not too close to each other.
# Output:

<img width="1028" height="552" alt="image" src="https://github.com/user-attachments/assets/9454edd8-b680-4e0a-823c-81a0d1426f74" />

# Result:

Thus, To Create a player movement using pawn, collectible, player health, and score createdand developed by unreal Engine.
