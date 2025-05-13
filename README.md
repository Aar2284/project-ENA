# project-ENA

ENA (**Everything Needed for Agriculture**) is a comprehensive, multi-module website designed to empower farmers and stakeholders in India’s agriculture sector. Built as part of a Student Innovation challenge (Problem No. 27 in Agriculture, FoodTech & Rural Development), ENA brings together several web-based tools and resources to streamline farming decisions, resource management, and feedback collection.

## 🗂️ Project Modules

1. **Seed Project** (`seedproject.html` + `style.css`)

   * Provides detailed information on seed varieties, sowing guidelines, and best practices for crop selection.
   * Includes responsive UI components styled with a dedicated CSS file.

2. **Solar Panel Guide** (`solarpanel.html` + `solarpanel.css`)

   * Explains how solar panels can power irrigation pumps and farm equipment.
   * Interactive diagrams and resource links to solar vendors.

3. **Weather Dashboard** (`weatherwebsite/index.html`)

   * Embeds a live weather widget to help farmers plan irrigation and harvesting.
   * Uses JavaScript to fetch and display real-time weather data.

4. **User Authentication** (`Login.html` + `Login.css`)

   * Basic login form to simulate secure access to ENA tools.
   * Error checking and styled inputs for a smooth user experience.

5. **Feedback System** (`Feedback.html` + `Feedback.css`)

   * Feedback form for users to submit suggestions or report issues.
   * CSS styling ensures a clean, accessible interface.

6. **Technical Resources** (`technical.html`)

   * Detailed technical documentation and flowcharts illustrating ENA’s architecture.

7. **Assets** (`images.zip`)

   * Contains all image assets (icons, diagrams, photos) used throughout the site.
   * Unzip into an `images/` folder at the project root.

## 🔧 Technologies Used

* **HTML5 & CSS3**: Semantic markup and modular styling for each page.
* **JavaScript**: Dynamic content loading and weather API integration.
* **Responsive Design**: Mobile-first approach so ENA works on both smartphones and desktops.
* **Static Website**: No backend required—simply open any HTML file in a modern browser.

## 🚀 Getting Started

1. **Clone or download** this repository to your local machine.
2. **Unzip** the `images.zip` file to create an `images/` directory alongside the HTML and CSS files.
3. **Open** `seedproject.html` in your web browser to start exploring ENA’s features.
4. Navigate between tools using links at the top of each page.

> **Tip:** Serve the folder using a simple HTTP server (`python -m http.server`) to avoid CORS issues when loading the weather widget.

## 🎯 How It Helps Farmers

* **Informed Decisions**: Choose the right seeds and planting schedules based on detailed guides.
* **Resource Optimization**: Learn about solar solutions to reduce electricity costs.
* **Real-Time Planning**: Check current weather conditions without leaving the dashboard.
* **Feedback Loop**: Report challenges directly to the development team for continuous improvement.

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome:

1. Unzip `images.zip` and ensure any new images go into `images/`.
2. Create a new branch: `git checkout -b feature/your-feature`.
3. Commit your changes and push to your fork.
4. Open a Pull Request detailing what you’ve added or fixed.

## 📄 License & Acknowledgments

* This project is released under the **MIT License**.
* Built by **Team Error 404** for Student Innovation Field (Agriculture, FoodTech & Rural Development).
* Special thanks to mentors and participating farmers for valuable feedback.
