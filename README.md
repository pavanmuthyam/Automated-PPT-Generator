# Automated-PPT-Generator

Automated Presentation Generator - Detailed Project Description Overview The Automated Presentation Generator is an AI-driven system that autonomously creates PowerPoint presentations with minimal user input. The tool integrates web scraping, NLP-based text summarization, and image extraction to generate structured, high-quality presentations efficiently. The project aims to reduce the time and effort required for creating presentations, making it particularly useful for educational and professional use.

Key Components & Technologies Web Scraping for Content Extraction

The system extracts textual and visual content from Wikipedia and other online sources. Uses BeautifulSoup and Selenium to parse HTML pages, identify key sections, and extract structured data. Extracts headings, subtopics, paragraphs, and images related to the given topic. Natural Language Processing (NLP) for Text Summarization

The extracted text is processed to remove unnecessary details and generate concise summaries. Uses advanced NLP models such as: BART (Bidirectional and Auto-Regressive Transformer): Denoising autoencoder trained for sequence-to-sequence tasks. XLNet: A generalized autoregressive model with bidirectional context modeling for high-quality summarization. The models ensure the generated content is coherent, concise, and retains essential information. Image Extraction and Captioning

Extracts relevant images from Wikipedia articles using BeautifulSoup. Captures image captions to provide context, using HTML tag parsing techniques. Uses OpenCV and PIL (Python Imaging Library) to overlay captions onto images. Ensures non-copyrighted images are used, primarily from Wikimedia Commons. Automated PowerPoint Generation

The summarized text and extracted images are structured into a well-formatted PowerPoint presentation. Uses the python-pptx library to: Create slides dynamically. Apply predefined templates and layouts. Organize content into titles, bullet points, and images. Supports graphical enhancements and data visualization for improved readability. Workflow User Input:

The user provides a topic as input. Content Extraction:

Web scraping gathers relevant text and images from Wikipedia. Extracted content is structured into headings and subheadings. Text Summarization:

The system cleans and processes the extracted text. NLP models generate concise and informative summaries. Image Processing:

Relevant images are extracted and annotated with captions. The system ensures only non-copyrighted images are included. PowerPoint Generation:

The processed text and images are formatted into slides. Layouts are optimized for visual appeal and readability. The final PPT file is generated and ready for use. Features & Benefits Time-Saving: Reduces the manual effort of researching and creating presentations. High-Quality Content: Uses state-of-the-art NLP models for accurate summarization. Automated Image Integration: Enhances slides with relevant visuals. Customizable & Scalable: Can be adapted for different topics and industries. Open-Source Libraries: Built using Python, BeautifulSoup, Selenium, NLP models, OpenCV, and python-pptx. Potential Applications Education: Helps teachers and students create study material quickly. Corporate Use: Automates report and presentation creation for businesses. Research & Journalism: Summarizes long documents into concise presentations. This project demonstrates the power of AI-driven automation in content creation and has the potential for further improvements, such as support for multiple sources, multi-language summarization, and real-time customization.
