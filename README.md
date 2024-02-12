
This will help you script a speedrunner game or a race game or any some sort speed related games, it's an part when touched it will change your speed to a certain number.

Let's look at this script that runs all the speed codes.

-- Made by ifqx1 at github or discord or roblox

script.Parent.Touched:Connect(function(hit) 
hit.Parent.Humanoid.WalkSpeed = 45 ← Here we have the number you may change it to the number of speed that you want the player to run/walk at it.
end)
