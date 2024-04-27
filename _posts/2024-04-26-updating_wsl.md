# Changing the WSL config files with the purpose of running Docker  

After setting up the container in WSL last week, I have been focusing on getting the GPU working and taking all of the necessary measures. To my suprise, after returning to the cpufrozen branch, it didn't work and my kernel kept on dying while trying to learn my model. 


My initial idea was to shutdown wsl as I assumend that it was just unstable again and needed to be reset. I did that and restartet my laptop for good measure but it didn't help. I saw the post about getting the memory in WSL extended but was initially worried that it could have done more bad then good. After a minute of consideration I concluded that it was the only way to have a chance at getting it fixed. I follow the instructions and suprisingly everything worked out of the box. This was an suprise as there have already been a lot of problems with setup for this exercise. Today I learned that the WSL is very flexible and that those setting can be changed without affecting the already setup system! This is without a doubt a really posivite side and a argument for using it more, as I now usually run everything on my dualbooted ubuntu system!
