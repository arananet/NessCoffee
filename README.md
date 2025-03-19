# NessCoffee Wake Up AR Game

This project is an engaging augmented reality (AR) game where players catch falling coffee beans using a virtual mug. The code includes all necessary components to create a fun and interactive coffee bean-catching experience.

## Key Implementation Features

1. **Core Game Structure**
   - Built using an Entity Component System (ECS) architecture
   - Full game lifecycle: placement, gameplay, and game over
   - Adjustable difficulty levels that affect bean spawn rates and behaviors

2. **3D Model Integration**
   - Incorporates models: `nescafe_mug.glb`, `Coffee_bean.glb`, `Star.glb`, and more
   - Distinct visual styles for regular beans and special beans
   - Environmental elements like sun and clouds for added atmosphere

3. **Interactive Gameplay**
   - Tap-to-place functionality for positioning the mug
   - Physics-based bean falling mechanics
   - Collision detection for catching beans in the mug
   - Dynamic scoring system based on player performance

4. **Power-Ups**
   - **Magnet**: Attracts beans toward the mug
   - **Time Boost**: Adds extra seconds to the game
   - **Double Points**: Multiplies scores for a limited time
   - Visual effects for power-up activation and deactivation

5. **Visual Effects**
   - Steam effects triggered when beans are collected
   - Particle systems for power-up activations
   - Floating score indicators for real-time feedback
   - Animations for all interactive game elements

6. **UI System**
   - Displays for score and remaining time
   - Notifications for power-up activation
   - Game over screen with a replay option
   - Countdown timers for game phases

## Technologies Used

- **AR-JS Library**: Powers the augmented reality functionality
- **Claude 3.7**: Used for development

## 3D Objects

- Nescafe mug converted from 2D to 3D using: [Stable Point-Aware 3D](https://huggingface.co/spaces/stabilityai/stable-point-aware-3d)

- **Assets**:

  - Coffee Bean: [poly.pizza/m/7ONZQTx9Tuz](https://poly.pizza/m/7ONZQTx9Tuz)
  - Steam Clouds: [poly.pizza/m/aQl2tRgDupm](https://poly.pizza/m/aQl2tRgDupm)
  - Star: [poly.pizza/m/fvTSBuNRhXM](https://poly.pizza/m/fvTSBuNRhXM)
  - Sun: [poly.pizza/m/77wHkzwlpOq](https://poly.pizza/m/77wHkzwlpOq)

## Sounds

- **Collect Sound**: By *wolfy_sanic* from [Pixabay](https://pixabay.com)
- **Power-Up Sound**: By *Ribhav Agrawal* from [Pixabay](https://pixabay.com)

## File List

- `Alarm_Clock.glb`
- `Cloud.glb`
- `Coffee_bean.glb`
- `nescafe_mug.glb`
- `Star.glb`
- `Sun.glb`
- `powerup.mp3`
- `collect_bean.mp3`

## Hosting the Game

To run the game, host the code on a local web server to avoid CORS (Cross-Origin Resource Sharing) issues.

## Working demo

Demo is available at this URL: https://arananet.net/ar

## Disclaimer

The nescafe_mug.glb model and any associated Nescafé branding used in this game are for demonstration purposes only. This project is not affiliated with, endorsed by, or sponsored by Nescafé or its parent company, Nestlé. The use of the Nescafé mug model does not imply any official partnership or commercial usage rights. Users are responsible for ensuring compliance with copyright and trademark laws if distributing or modifying this game for non-personal use.

## Developer

- **Name**: Eduardo Arana
