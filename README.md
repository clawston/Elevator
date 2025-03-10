First, the "Simple Elevator" will run the bare bones basics of the question asked- simply returning a list of floors, and total time taken. It is a simplificiation of the problem with many assumptions, such as constant time for up/down, and no routing/optimization of destinations.
It will not work if any of the floors entered are not integers.

<img width="601" alt="elvator_simple" src="https://github.com/user-attachments/assets/6d39c498-a33e-407d-b8f6-39b2f7e0371e" />



Next, a more complex elevator was created.  This one has an option to "optimize" the path taken by applying a heuristic to route floors.  

<img width="434" alt="elevator_optimized" src="https://github.com/user-attachments/assets/2b4807c8-92e5-411d-9457-b27ed78e68df" />

It also has the capability to graphically plot the floors visited.

<img width="434" alt="elevator_plot" src="https://github.com/user-attachments/assets/d49e283e-9456-4fc5-a3a3-9a49dbf6f4a1" />

Additionally, it features a different travel time for going up vs. down, as well as a 5% random chance of the elevator getting stuck and delaying.



Lastly, an "Intergalactic Elevator" was constructed, allowing passengers to travel in the X,Y,&Z dimensions to their floors.  It uses K-Means clustering to group passengers based on where their destination is generally located, then send them to a different elevator for that area. It then uses the same routing optimization to quickly hit all destinations in the area.

<img width="315" alt="elevator_intergalactic" src="https://github.com/user-attachments/assets/ba012b3d-5240-4626-b05e-51bafdf851fa" />
