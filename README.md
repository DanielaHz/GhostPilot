
This project focuses on teaching a real drone how to move autonomously by first training it inside a photorealistic Unreal Engine simulation. Using reinforcement learning, the drone learns basic and advanced movement behaviours—such as stabilising itself, navigating through environments, and avoiding obstacles—before the trained model is transferred to the physical drone.

## Envrionment Reference
The drone's trajectory begins in the living room and proceeds up a staircase. At the landing, it moves forward into the hallway, makes a left turn, and continues ascending the next stair segment.

The operational environment presents several structural limitations. The staircase is narrow, restricting horizontal manoeuvrability, and the hallway features irregular roof geometry that reduces and varies the available vertical clearance. Additional architectural elements—such as angled ceilings, protrusions, and elevation changes—introduce further obstacles that increase the complexity of autonomous navigation.

![](/assets/environment.png)

## Drone Model

The drone used in this project is the DJI Ryze Tello. It includes a vision‑positioning system with a downward‑facing camera and a 3D infrared module located on the underside of the aircraft. The drone operates at altitudes ranging from 1 to 98.4 ft. Its specifications are:

### Specifications
|Model| TLW004 | 
| --- |--- | 
|Weight| 87 gr | 
|Max Speed| 28.8 kph | 
|Max flight time| 13 minutes | 
|Max image size| 2592x1936 |
|Video recording | HD: 1280x720 |
| FPS | 30 |
| Video format | MP4 |

![](/assets/drone-model.png)


## Project Overview 

- Create a virtual replica of the tree eenvironemntes living room, tairs and room.

- Train a virtual drone using reinforcement learning, allowing it to learn movement, stability, and navigation behaviours through interaction with the simulated environment.

- Enable the drone to understand and react to the virtual space, learning how to avoid obstacles, follow paths, and move autonomously based on sensor inputs.

- Export the trained policy and deploy it on a real Ryze Tello (DJI), enabling the physical drone to perform autonomous movement in the real world using the skills learned in simulation.

- ![](/assets/drone_rl_sim_to_real_pipeline.svg)

## Tools


