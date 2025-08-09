# Random Says 1.1

## Project Description

**Random Says 1.1** is an innovative AI-powered mobile application designed to enhance communication skills through dynamic rehearsal and feedback. This app serves as a personal communication coach, offering a suite of specialized modes to help users plan, practice, and refine their conversational abilities for a variety of social and professional scenarios.

The project is currently under active development.

## Key Features

The app is being built with the following core modes and features:

* **RRF Mode (Refined Response Mode):** Provides constructive feedback and copy-and-pasteable alternative versions for any user-inputted message.
* **ARR Mode (Agreed Refirmed Response Mode):** Helps users formulate polite and effective agreements with added emphasis.
* **DRR Mode (Disagreed Refirmed Response Mode):** Trains users to express disagreement fluently and constructively.
* **CRR Mode (Convo Refirm Rehearsal):** A dynamic conversation simulator that tracks progress toward a user-defined goal, providing real-time feedback.
* **OCR Mode (Opposing Contradictory Response Mode):** A unique tool for exploring antonyms and opposing ideas to a given word, phrase, or sentence.

## Getting Started

This repository contains the source code for the mobile application. To get a local copy up and running, follow these simple steps.

### Prerequisites

* Node.js (for the React Native front-end)
* Python 3.x (for the Flask/Django back-end)
* Access to a large language model (LLM) API, such as OpenAI's GPT or similar services.

### Installation

1.  **Clone the repo:**
    ```sh
    git clone [https://github.com/your-username/random-says-1.1.git](https://github.com/your-username/random-says-1.1.git)
    cd random-says-1.1
    ```

2.  **Set up the front-end (mobile app):**
    ```sh
    cd mobile-app
    npm install
    # For iOS: npx pod-install
    ```

3.  **Set up the back-end (AI server):**
    ```sh
    cd back-end
    pip install -r requirements.txt
    ```

4.  **Configure API Keys:**
    You will need to add your LLM API key to the back-end configuration. Create a `.env` file in the `back-end` directory with the following content:
    ```
    OPENAI_API_KEY=your_api_key_here
    ```

## Usage

* **Run the back-end server:**
    ```sh
    cd back-end
    python app.py
    ```
* **Run the mobile app:**
    ```sh
    cd mobile-app
    npx react-native run-ios  # or npx react-native run-android
    ```

## Technology Stack

* **Front-End:** React Native
* **Back-End:** Python (Flask)
* **AI/ML:** Custom prompts and logic leveraging a large language model (e.g., OpenAI API)

## Contributing

Contributions are what make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

---

**Note:** This README assumes a standard project structure with `mobile-app` and `back-end` directories. Adjust the file paths and commands as needed for your specific project layout.
