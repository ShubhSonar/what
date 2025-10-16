What? 🤔
=

What? 🤔 is a Chrome extension designed to enhance your critical thinking process when consuming online information. Leveraging the power of Gemini Nano, **Google's built-in AI model**, it provides an elegant interface for questioning and exploring any text you encounter on the web. It empowers users to delve deeper into content without manual search, fostering a more efficient learning experience.

## Key Features

*   **AI-Powered Question Generation:** Analyzes selected text and generates insightful critical reasoning questions using Gemini Nano, **Google's built-in AI model.**
*   **Contextual Explanation:** Provides an initial explanation of the selected text for better understanding.
*   **Seamless Web Search:** Offers direct access to search results related to generated questions with a single click, eliminating manual query construction.
*   **Multi-lingual Support:** Enables critical thinking on non-English content through "PROMPT API for Gemini Nano with multi-lingual mode".
*   **User-Friendly Interface:** Simple and intuitive design for effortless integration into your workflow.

## How it Works

1.  **Enable the Extension:** Install What? 🤔 from the Chrome Web Store: [https://chromewebstore.google.com/detail/what-%F0%9F%A4%94/olohgpigdeeoabcgcmkblncaceafhjcn](https://chromewebstore.google.com/detail/what-%F0%9F%A4%94/olohgpigdeeoabcgcmkblncaceafhjcn)
2. **Enable Prompt API:** Enable prompt API for Google nano model. For same go to ``chrome://flags`` in address bar and search ``Prompt API for Google Nano``.
3.  **Select Text:** Highlight the text you want to analyze on any webpage.
4.  **Generate Questions:** ``What? 🤔`` action will generate a greeting message, an initial explanation and critical questions based on your selection. 
5.  **Explore Further:** Click the ``Search`` button next to each question for instant results.

## Important Considerations & Setup:

- This is an experimental extension leveraging the Gemini Nano API, which may have device compatibility limitations. Please ensure your device meets the requirements outlined in chrome://flags.
- Initially runs may take a few minutes or long time to return a response as it downloads the Gemini Nano model file.
- Please enable the "PROMPT API for Gemini Nano (multi‑lingual)" setting in Chrome's experimental features (chrome://flags).
- For optimal performance, consider enabling the "optimization guide on device" flag. (See chrome://flags for details.)
- Check the model status at chrome://on-device-internals
- I recommend using this extension initially for personal purposes on non-production devices – as noted in chrome://flags.

This extension will significantly enhance your research & learning process 😊

## A few sample use cases to start with

*   **Deep Dive into Articles:** Uncover underlying assumptions and potential biases in news articles or blog posts.
*   **Code Comprehension:**  Question code snippets to understand their logic, edge cases, and security implications.
*   **Academic Research:** Generate questions to guide your research process and identify areas for further investigation.
*   **Content Analysis:** Critically evaluate online content from sources like LinkedIn, Reddit, or social media posts.
*    **Non-English Content**:  Understand complex non-english contents with ease

## Technical Details

*   **Extension Code:** [src folder](src/) - Contains the source code for the Chrome extension.
*   **Content.js:** File enables users with the ``What? 🤔`` action. Clicking on same, the selected data from the page is used to input into inbuilt Gemini Nano model via PROMPT API.

## Resources

*   **YouTube demo (3 minutes):** [https://www.youtube.com/watch?v=1irBEI9yWDw](https://www.youtube.com/watch?v=1irBEI9yWDw)
*   **Extended demo with examples (33 minutes):** [https://www.youtube.com/watch?v=7gvnDxKPBl8](https://www.youtube.com/watch?v=7gvnDxKPBl8)
