# 🚗 Dream Car Generator

A vanilla, frontend-only web application that allows users to design and visualize their custom "dream car." By selecting various specifications like era, passenger count, styling, and drivetrain, the application dynamically engineers a prompt and generates a photorealistic render using the free Pollinations AI image API.

## 📑 Table of Contents
- [Features](#-features)
- [Technologies Used](#-technologies-used)
- [Installation](#-installation)
- [Usage](#-usage)
- [Contributing](#-contributing)
- [License](#-license)

## 🚀 Features
* **AI Image Generation:** Seamlessly integrates with the Pollinations.ai API to render high-quality, 8K commercial automotive photographs.
* **Dynamic Prompt Engineering:** Automatically constructs detailed AI prompts based on form inputs to ensure accurate and dramatic results.
* **No Authentication Required:** Works entirely without API keys or backend setup thanks to the public Pollinations API.
* **Responsive UI:** Clean, modern, and fully responsive user interface featuring loading states and prompt visibility.

## 💻 Technologies Used
* **HTML5:** Semantic structure and form elements.
* **CSS3:** Custom styling, CSS variables, and responsive design (no external frameworks).
* **Vanilla JavaScript:** DOM manipulation, form handling, and dynamic URL generation.
* **Pollinations.ai API:** AI image rendering service.

## 🛠️ Installation

Since this is a static frontend application with no build steps or dependencies, installation is incredibly simple:

1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/dream-car-generator.git](https://github.com/yourusername/dream-car-generator.git)
   ```
2. Navigate to the project directory:
   ```bash
   cd dream-car-generator
   ```
3. Open `index.html` directly in your preferred web browser. No local server is required.

## 💡 Usage

1. Open the application in your browser.
2. Select your desired car parameters:
   * **Era / Time Period** (e.g., Modern, Retro-Futuristic)
   * **Passenger Count** (1-9)
   * **Exterior Color** (e.g., Metallic Emerald Green)
   * **Exterior Styling** (e.g., Aggressive and muscular)
   * **Drivetrain** (e.g., AWD, 4x4 High-Clearance)
3. Click the **"Show Car"** button.
4. Wait for the loading indicator to finish (usually under 10 seconds). The generated rendering and the exact prompt used will appear at the bottom of the screen.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! 

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
