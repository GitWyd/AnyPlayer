# Adaptive Reinforcement Learning Framework for Browser and Flash Games (ARLF-BFG)

## Description
ARLF-BFG is a Python-based reinforcement learning framework designed for automating and learning from browser and flash games. It uniquely integrates user demonstrations, OCR, and custom-configurable reward functions for a versatile learning environment.

## Key Features
1. **Game Compatibility**: Supports various browser and flash games, configurable via JSON/YAML files.
2. **User Demonstration Interface**: Allows gameplay demonstration for strategy learning.
3. **Dynamic Screen Analysis**: Uses OCR for in-game feedback (scores, lives, currency) from user-defined regions.
4. **Customizable Reward Function**: Assign weights to in-game metrics in config files.
5. **Continuous Learning Approach**: Handles non-stepwise, continuous game environments.
6. **Extensibility and Scalability**: Easily adaptable to new games and updates.
7. **Robust Learning Algorithms**: Suitable for environments with delayed rewards.
8. **User-Friendly Setup**: Streamlined game setup and learning progress monitoring.

## Usage Scenarios
- Automating gameplay in browser or flash games.
- Low skill entry point for AI and machine learning research on games outside of AI Gym integrated games
- Development experiments with OCR in reinforcement learning.
  
## Platform Compatibility
Our development and compatibility efforts are prioritized as follows:
1. **Ubuntu (Primary Focus)**: The framework is first and foremost developed for Ubuntu. This ensures compatibility with a wide range of Linux environments, which are often preferred in the AI and machine learning communities.
2. **macOS (Secondary Focus)**: Post Ubuntu compatibility, we will focus on adapting the framework for macOS, ensuring it runs smoothly on Apple's operating systems.
3. **Windows (Tertiary Focus)**: Windows compatibility is our third priority. Efforts to adapt and optimize the framework for Windows will follow after Ubuntu and macOS versions are stable and reliable.

This prioritization allows us to concentrate our efforts effectively, catering first to platforms most commonly used in development and research, followed by broader user accessibility.

## Development Philosophy: Rapid Deployment
The primary goal of ARLF-BFG is to launch a functional version as quickly as possible. In line with this, we embrace the following principles:
- **Pragmatic Approach**: Prioritize functionality over perfection. Cut corners where necessary, without compromising the core integrity of the framework.
- **Leverage Existing Solutions**: Utilize existing packages, libraries, and code snippets extensively. Reinventing the wheel is not our objective.
- **Iterative Development**: Release early and iterate. Initial versions may lack polish, but we aim for continuous improvement based on user feedback and testing.
- **Open to Shortcuts**: We welcome any shortcuts, hacks, or unconventional methods that can accelerate development, provided they adhere to legal and ethical standards.

Contributors are encouraged to keep this rapid deployment philosophy in mind. Our goal is to create a working prototype swiftly, setting the foundation for future refinement and enhancement.

## Contribution Guidelines
Contributions are welcome for game configurations, algorithm enhancements, OCR improvements, and documentation updates. See our contributing document for more details.

## License
MIT License

## Disclaimer
This framework is for educational and research purposes only. Adherence to game terms of service is the user's responsibility.
