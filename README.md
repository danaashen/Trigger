🧲 Magnetic Attraction — Interactive SwiftUI App
A dynamic and playful SwiftUI application that explores particle physics, real-time state management, and fluid animations. The core concept revolves around a "Magnetic Field" that manipulates chaotic elements on the screen through user interaction.

🌟 Concept Overview
Unlike traditional static interfaces, Magnetic Attraction offers a tactile experience. The screen acts as a container for free-floating "molecular" spheres that instantly react to the activation of a central magnetic force.

Key Visual Effects:

Chaotic Drift: 20–30 vibrant spheres constantly float across the screen, simulating a living, microscopic environment.

Magnetic Pull: Upon holding the "MAGNET" button, all spheres rush toward the center from every corner of the screen with an audible whistle, clumping together to form a pulsating, glowing ring around the button.

Kinetic Explosion: Releasing the button triggers a "Supernova" effect, where the spheres blast outward at high velocity in random directions.

Immersive Audio: Integrated sound effects provide sensory feedback—a deep magnetic hum during the pull and a sharp "pop" or "blast" during the explosion.

🛠 Technical Stack
This project is built using modern declarative programming principles:

SwiftUI State Management: Efficiently tracking the positions and properties of dozens of individual particles using @State.

Physics-Based Animations: Utilizing .spring(response: 0.4, dampingFraction: 0.6) to create a realistic "bouncy" effect as spheres collide with the magnetic core.

Gesture Interaction: Custom handling of press-and-release states to maintain the magnetic field in real-time.

AVFoundation: Audio engine integration to sync high-fidelity sound effects with visual transitions.

🚀 How It Works
Generation: On launch, an array of objects is generated with randomized starting coordinates and colors.

Transformation: When the magnetic state is triggered, the coordinates of all particles are recalculated to converge on the button's center point.

Animation: withAnimation interpolates the movement, creating a smooth flight path for every particle.

Feedback: The app triggers haptic feedback and synchronized audio to enhance the physical "feel" of the magnetic pull.
