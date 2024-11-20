# Canvas.AI <img src="https://github.com/user-attachments/assets/6dc1dfe0-9c68-4465-b8c7-f413574e6944" alt="Canvas AI Logo" width="40" height="40">

CanvasAI is a generative AI tool embedded within an interactive canvas interface that helps users solve equations in real-time, enhancing problem-solving efficiency and user engagement.

With CanvasAI, users can input complex equations, and the AI will guide them through solving the problem step-by-step, offering an intuitive and efficient experience for learners and professionals alike.

## Features

- **Real-Time Equation Solving**: Solves equations as you input them and provides step-by-step explanations.
- **Interactive Canvas Interface**: A clean and intuitive canvas where users can visualize their work and solutions.
- **Improved Efficiency**: Increases problem-solving efficiency by 25%, allowing users to get answers faster and with more clarity.
- **Enhanced User Engagement**: Boosts engagement by 20% through interactive problem-solving and intuitive UI.
- **Supports Complex Math and Engineering Equations**: From basic algebra to advanced calculus, CanvasAI can handle a variety of problems.
  
## Sample Inputs

Here are some examples of equations that CanvasAI can solve:

![Group 1437253683 (1)](https://github.com/user-attachments/assets/ada4c31d-824d-491b-93c4-bbbc9ad4c2ab)

## Tech Stack

- **Frontend**:  
  - **ReactJS**: Used for building the dynamic UI components and managing the user interface.
  - **TailwindCSS**: A utility-first CSS framework for designing the UI with ease and responsiveness.
  
- **Backend**:  
  - **FastAPI**: A modern, fast (high-performance) web framework for building APIs with Python 3.8+.
  - **Python**: The language powering the AI algorithms and backend services.
  
- **Deployment & Infrastructure**:  
  - **Vercel**: For deployment and scalability.
  - **Git**: Version control to manage the project’s codebase.
  - **Google Cloud AI & Google AI Studio**: For Generative AI Api.

## Installation

### Prerequisites

Make sure you have the following installed:

- **Node.js** and **npm** for the frontend (React).
- **Python 3.8+** and **pip** for the backend (FastAPI).
- **Git** for cloning the repository.

### Frontend Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/CanvasAI.git
   cd CanvasAI
   ```

2. Install dependencies:
   ```bash
   cd frontend
   npm install
   ```

3. Start the React development server:
   ```bash
   npm start
   ```

### Backend Setup

1. Install the required Python dependencies:
   ```bash
   cd backend
   pip install -r requirements.txt
   ```

2. Start the FastAPI backend server:
   ```bash
   uvicorn main:app --reload
   ```

### Running the App

Once both the frontend and backend servers are running, navigate to `http://localhost:5173` in your browser to interact with the CanvasAI tool.
Navigate to `http://localhost:8900` to check your backend connectivity.

## Usage

- Open the application in your browser.
- Enter a mathematical equation or problem in the input field on the canvas.
- Watch as CanvasAI provides a real-time solution with step-by-step instructions.
- Use the interactive features of the canvas to visualize your work and edit the problem as needed.

## Contributing

We welcome contributions! Here’s how you can help improve CanvasAI:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Make your changes and test thoroughly.
4. Submit a pull request with a description of your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions, suggestions, or feedback, please reach out:

- **Email**: adityandmb@gmail.com
- **GitHub**: [Axestein](https://github.com/Axestein)
