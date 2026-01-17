# LITA
Loguidice Interactive Text Analyzer (LITA). Provides a comprehensive, real-time analysis of any text you paste or type into it.

Link to the active Web version: https://bill-loguidice.itch.io/lita-loguidice-interactive-text-analyzer

v2.0

LITA™ is a browser-based, real-time text analysis tool designed to help writers, editors, and technical communicators audit their content for readability, rhythm, and style.


Core Functionality

- Real-Time Analysis: Instantly calculates metrics as you type or paste text, with no server-side processing required (everything happens in the browser!).
- Dual View Modes:
	- Write Mode: A distraction-free text entry area.
	- Preview Mode: A Markdown renderer that formats your text (headers, lists, bold/italics) for easy review.
- Auto-Save: Your text is automatically saved to the browser's local storage, preventing data loss if the tab is closed.

Detailed Metrics Dashboard

The app breaks down analysis into three tiers:
1. Basic Counts: Words, Characters, Letters (A-Z), Sentences, Paragraphs, and Unique Words.
2. Readability & Flow:
	- Reading Level: Uses the Flesch-Kincaid Grade Level formula (e.g., "Grade 10," "College").
	- Reading Time: Estimates time to read based on 225 words per minute.
	- Averages: Average word length and average sentence length.
	- Longest Word: Identifies and displays the longest single word in the text.
3. Stylistic Checks:
	- Passive Voice: Detects and counts potential passive voice usage (e.g., "was done").
	- Adverbs: Tracks the usage of "-ly" adverbs to help tighten prose.

Visualizations

- Sentence Rhythm Graph: A dynamic bar chart at the bottom visualizes the length of every sentence in your text. This helps you "see" the rhythm of your writing—jagged lines indicate good variety, while flat lines indicate monotony.
- Keyword Density: A list of the most frequent words (excluding common "stop words" like the, and, is) to help with SEO or avoiding repetition.

Utilities and UI

- Theme Support: A fully functional Dark Mode toggle that persists with your preference.
- Export Reports: Generates a downloadable .txt report containing all current statistics and the full body text.
- Safety Features: A custom confirmation modal prevents accidental deletion when clicking the "Clear" button.

---

Core Analysis Metrics

- Real-Time Statistics: Instantly calculates word, character, sentence, and paragraph counts as you type or paste content.
- Reading Time Estimation: Provides an estimated reading time based on a standard 225 WPM average, adjusting dynamically for short snippets or long-form articles.
- Flesch-Kincaid Grading: Automatically assesses the reading level of your text, categorizing it from "Pre-K" through "Post-Grad" to ensure your content matches your target audience.

Stylistic & Editorial Tools

- Passive Voice Detector: Identifies potential instances of passive voice (e.g., "was done") to help writers strengthen their prose.
- Adverb Monitor: Tracks the usage of "-ly" adverbs, alerting writers to potential over-reliance on modifiers rather than strong verbs.
- Keyword Density Analysis: Filters out common stop words to reveal the most frequently used unique terms and their percentage density, useful for SEO optimization and avoiding repetition.

Visualizations & Rhythm

- Sentence Rhythm Graph: A dynamic bar chart visualizes the "shape" of your writing by plotting the length of every sentence. This allows writers to instantly spot monotony (flat lines) or confirm good flow (varied peaks and valleys).

Productivity Features

- Dual View Modes: 
	- Write Mode: A A distraction-free environment for drafting and editing.
	- Preview Mode: A built-in Markdown renderer that instantly formats your text (headers, lists, bold/italic) for review.
- Report Export: Generates and downloads a .txt summary report containing all current statistics and the full text body for documentation tickets or editorial archives.
- Theme Support: Fully integrated Dark Mode for reduced eye strain during low-light writing sessions.
- Auto-Save functionality: If you accidentally refresh the page or close the tab, your text will be there when you come back. Your browser's local storage is used.
- Privacy-First: All analysis is performed client-side in the browser; no text is ever sent to an external server.
