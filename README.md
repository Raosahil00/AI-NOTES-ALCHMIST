# ✨ AI Note Alchemist
## 💡 Overview

AI Note Alchemist is an innovative web application designed to enhance the study experience by transforming raw text into structured, aesthetically pleasing **"handwritten"** study notes, complete with diagrams and interactive learning tools.

This tool addresses the common challenge of converting dense digital material into easily digestible, visually stimulating content, mimicking the cognitive benefits of physically taking notes.

## 🌟 Key Features

  * **📝 Handwritten Aesthetic:** Converts standard input text into a charming, personalized handwriting style using the **Patrick Hand** font and custom canvas drawing.
  * **🤖 AI-Powered Structuring:** Utilizes the Google Gemini API to analyze the input and automatically structure the notes into professional learning components:
      * **Definition Boxes:** Highlights and frames key concepts.
      * **Bullet Lists:** Organizes key takeaways.
      * **Flowcharts:** Creates step-by-step process diagrams for sequences and processes.
  * **👶 "Explain Like I'm 5" Mode:** A dedicated function to simplify complex topics into rudimentary concepts before generating the notes.
  * **🧠 Interactive Quizzing:** Generates a 5-question multiple-choice quiz automatically based on the content of the notes for immediate self-testing.
  * **💬 Contextual AI Tutor:** Features an "Ask AI" modal that allows users to ask follow-up questions, with the AI answering based specifically on the provided text context.
  * **📄 High-Quality PDF Export:** Enables multi-page export of the fully rendered notes (including the background paper lines and margins) into a clean PDF document using **jsPDF**.
  * **🎨 Sketchy Visualization:** Graphics (boxes, flow lines, bullets) are rendered with a hand-drawn, imperfect look using the **rough.js** library.

## 💻 Tech Stack

| Category | Technology | Purpose |
| :--- | :--- | :--- |
| **Generative AI** | Google Gemini API (`gemini-2.5-flash-preview`) | Text analysis, structuring, quiz generation, and contextual Q\&A. |
| **Frontend Core** | HTML5, CSS3, Vanilla JavaScript | Application logic and structure. |
| **Graphics** | HTML5 Canvas API | Low-level drawing, background paper lines, and layout management. |
| **Sketch Visualization** | Rough.js | Renders hand-drawn, sketchy shapes for boxes and flowcharts. |
| **Document Export** | jsPDF | Client-side generation and download of the multi-page PDF notes. |

## ⚙️ Installation and Usage

This project is entirely client-side, making deployment straightforward.

1.  **Clone the repository:**

    ```bash
    git clone [YOUR_REPO_URL]
    ```

2.  **Add API Key:**

      * Obtain a Google Gemini API key.
      * Paste your key into the `apiKey` variable in the `INDEX.html` `<script>` block (e.g., `const apiKey = "YOUR_API_KEY";`).

3.  **Run Locally:**

      * Open `INDEX.html` directly in your web browser.

4.  **How to Use:**

      * Paste your study material into the central text area.
      * Click **"Generate Notes"** for standard formatting or **"Explain Like I'm 5"** for simplification.
      * View the generated notes, navigate pages, and use the **"Quiz Me"** or **"Ask AI"** functions.
      * Download your finished notes using the **"PDF"** button.

-----
