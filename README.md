    # Kannada Learning Helper

    A simple web application designed to help users learn to read and pronounce basic Kannada words and sentences.

    ## Features

    * Displays Kannada words and sentences from different lessons.
    * Text-to-Speech functionality to listen to the pronunciation (requires browser support for Kannada voice).
    * Speech Recognition functionality to practice pronunciation (requires browser support and microphone access).
    * Validation feedback (Correct/Incorrect) based on speech input.
    * Progress bar to track learning progress.
    * Randomization of items within early lessons for replayability.
    * Responsive design for use on tablets and desktops.

    ## Lessons Included

    1.  Lesson 1: Simple Words (100 items, randomized)
    2.  Lesson 2: Two-Word Sentences (100 items, randomized)
    3.  Lesson 3: Three-Word Sentences (100 items, randomized)
    4.  Lesson 4: Longer Sentences (Sequential)

    *(Note: The current word/sentence lists are samples and can be expanded in `index.html`)*

    ## How to Use

    1.  Clone this repository or download the `index.html` file.
    2.  Open the `index.html` file in a modern web browser (like Chrome, Firefox, Edge) that supports the Web Speech API (SpeechSynthesis and SpeechRecognition).
    3.  Use the "ಕೇಳಿ" (Listen) button to hear the pronunciation.
    4.  Use the "ಹೇಳಿ" (Speak) button to record your voice and get validation. You will need to grant microphone permission when prompted.
    5.  Use the "ಹಿಂದಿನದು" (Previous) and "ಮುಂದಿನದು" (Next) buttons to navigate. The "Next" button is enabled only after correct pronunciation.

    ## Deployment

    This project is a static HTML file and can be deployed easily on platforms like:

    * [Vercel](https://vercel.com/)
    * [Netlify](https://www.netlify.com/)
    * [GitHub Pages](https://pages.github.com/)

    Simply connect your GitHub repository containing this `index.html` file to your chosen platform.

    ## Technologies Used

    * HTML5
    * Tailwind CSS (via CDN)
    * JavaScript (ES6+)
    * Web Speech API (SpeechSynthesis & SpeechRecognition)
    * Font Awesome (for icons, via CDN)
    * Google Fonts (Noto Sans Kannada)
    
