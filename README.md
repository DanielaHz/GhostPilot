
This project focuses on teaching a real drone how to move autonomously by first training it inside a photorealistic Unreal Engine simulation. Using reinforcement learning, the drone learns basic and advanced movement behaviours—such as stabilising itself, navigating through environments, and avoiding obstacles—before the trained model is transferred to the physical drone.

## Project Overview 

- Create a virtual replica of my living room using photogrammetry and Gaussian Splatting.
This reconstructed environment is then imported into Unreal Engine 5 to serve as a realistic training space.

- Train a virtual drone using reinforcement learning, allowing it to learn movement, stability, and navigation behaviours through interaction with the simulated environment.

- Enable the drone to understand and react to the virtual space, learning how to avoid obstacles, follow paths, and move autonomously based on sensor inputs.

- Export the trained policy and deploy it on a real Ryze Tello (DJI), enabling the physical drone to perform autonomous movement in the real world using the skills learned in simulation.

- ![](/assets/drone_rl_sim_to_real_pipeline.svg)

