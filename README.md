# GUVI-Multilingual-GPT-Chatbot
GUVI CHATBOT
# Problem Statement
Building a multilingual chatbot capable of understanding and responding to user queries in multiple languages presents a unique challenge. The chatbot must translate non-English inputs 
into English, process these using a fine-tuned GPT model, and then translate the responses back to the user’s original language. This ensures seamless, accurate, and natural interactions 
across different languages.

The chatbot should be deployed on platforms like Hugging Face Spaces or AWS, featuring a clean and interactive UI to provide real-time conversational assistance. This will enhance the 
learning experience for GUVI platform users by offering personalized support in their preferred language.

## Project Overview
This project focuses on developing a multilingual GPT-based chatbot integrated with translation capabilities. 
Utilizing pre-trained or fine-tuned models from Hugging Face, the chatbot dynamically handles input translation, response generation, and output translation to support a 
variety of languages.
The user interface is implemented using Gradio for quick and efficient deployment, allowing real-time interaction via a web browser. 
The solution aims to improve accessibility and user engagement on the GUVI learning platform by breaking language barriers and providing personalized, intelligent assistance.

### Domain 
- Artificial Intelligence / Natural Language Processing / Web Development

This project leverages deep learning models (GPT) within the AI domain to understand and generate natural language. 
It uses NLP techniques for language detection, translation, and response generation. 
The chatbot interface is developed as a web application using Gradio, enabling real-time user interactions over the web.

#### Goals
- Build a multilingual chatbot that can understand and respond in multiple languages.
- Integrate translation capabilities to convert user input to English and responses back to the original language.
- Deploy a real-time, interactive chatbot with a clean and user-friendly interface.
- Enhance accessibility and user engagement on the GUVI platform.
- Maintain modular, maintainable, and scalable code with proper version control.

#### Key Input Features
- User text input in any supported language.
- Automatic language detection to identify the input language.
- Translation of non-English inputs into English for processing.
- Fine-tuned GPT model to generate accurate and relevant responses.
- Translation of GPT responses back to the user's original language.
- Support for real-time conversational flow with quick response times.

### Highlights
- Seamless multilingual support with automatic language detection and translation.
- Integration of fine-tuned GPT models for accurate and context-aware responses.
- Real-time interaction through a clean and intuitive Gradio web interface.
- Modular and scalable architecture for easy maintenance and future enhancements.
- Deployment-ready on platforms like Hugging Face Spaces and AWS.

### Business Use Cases:
**1. Customer Support Automation**  
- Scenario: Organizations receive customer queries in various regional languages, but most automated systems only understand English.
- Application: The chatbot can automatically translate incoming queries to English, process them using the fine-tuned model, and respond in the user's language, enabling 24/7 multilingual support 
                without hiring additional language experts.

**2. E-Learning Platforms**
- Scenario: Educational platforms like GUVI serve a multilingual audience, but automated chat support is often limited to English, creating a barrier for non-English-speaking users.
- Application: The multilingual chatbot can interact with students in their native languages, assisting with course inquiries, enrollment help, and technical support, thereby enhancing 
accessibility and user satisfaction

**3. Career Guidance and Mentorship Assistant**
- Scenario: Leverage the GPT model to offer career suggestions and roadmaps to learners based on their interests and skill levels.
- Application: The chatbot can suggest learning paths (e.g., Full Stack, Data Science), connect learners to relevant resources, and simulate basic career counseling.

**4. Course Discovery and Recommendation**
- Scenario: Assist users in finding the right course based on their interests, goals, or current skill level.
- Application: The GPT model can ask a few questions to the user and recommend specific GUVI courses, certifications, or masterclasses.

### Technologies Used
This project primarily uses Python along with several specialized libraries and tools to build, deploy, and manage the multilingual chatbot:

- **Hugging Face Transformers:** For accessing and fine-tuning powerful pre-trained language models like GPT.  
- **Gradio                   :** To create an easy-to-use and shareable web interface for the chatbot.  
- **Deep Translator          :** Enables translation between multiple languages to support multilingual conversations.  
- **Langdetect               :** Automatically detects the language of user input to trigger the correct translation pipeline.  
- **FuzzyWuzzy & Python-Levenshtein:** Provides robust fuzzy string matching to improve FAQ query handling.  
- **Pandas & NumPy           :** Used for efficient data manipulation and numerical operations during preprocessing.  
- **Git                      :** Version control to track code changes and collaborate efficiently.

### Tools Used
- **Python                 :** Primary programming language for development.  
- **GitHub                 :** Repository hosting and version control platform for managing the project codebase.  
- **Hugging Face Hub       :** Platform to access, download, and fine-tune pre-trained models.  
- **Google Colab           :** For experimentation, data preprocessing, and model fine-tuning in an interactive environment.  
- **Hugging Face Spaces    :** Deployment platform used to host the chatbot web app with Gradio interface.  
- **Command Line / Terminal:** For running scripts, installing packages, and version control operations.

#### Setup, Installation & How to Run
- This project is designed to run primarily in a Google Colab environment with minimal setup:
   - 1. **Open the provided Colab notebook** containing the project code.
   - 2. **Run all cells sequentially** to install required libraries, load models, and launch the chatbot interface.
   - 3. Once the Gradio interface launches, it will provide a **public URL** to access the chatbot.
   - 4. **Interact with the chatbot** directly through the web interface in your browser via the provided URL.

### Approches
- 1. **Model Selection**  
   - Chose pre-trained GPT-based language models from Hugging Face for generating human-like responses.  
   - Selected translation models (e.g., MarianMT) to handle multilingual input/output dynamically.
- 2. **Translation Pipeline**  
   - Detected user input language using `langdetect`.  
   - Translated non-English inputs to English before feeding them into the GPT model.  
   - Translated GPT-generated English responses back to the user’s original language.
- 3. **Chatbot Interface**  
   - Built a simple, user-friendly web interface using Gradio for real-time interaction.  
   - Enabled automatic launching of a public URL for easy sharing and access.
- 4. **Data Preparation & Fine-Tuning**  
   - Used domain-specific GUVI data in English to fine-tune the GPT model for relevant responses.  
   - Cleaned and preprocessed text data to improve model accuracy.
- 5. **Deployment Strategy**  
   - Hosted the chatbot on Hugging Face Spaces via Gradio for scalable and accessible deployment.  
   - Ensured low latency and smooth user experience.
- 6. **Error Handling & User Feedback**  
   - Implemented graceful handling of unsupported languages and model errors.  
   - Provided clear messages and fallback options to users.
 
##### Hugging Face URL - https://huggingface.co/spaces/logith02/guvi_chatbot4

## Conclusion
This project successfully demonstrates the development of a multilingual chatbot that leverages state-of-the-art GPT models integrated with dynamic translation capabilities. 
By combining advanced AI and NLP techniques with an easy-to-use Gradio interface, the chatbot breaks language barriers and delivers personalized, real-time support to users across 
different languages. Deployed on scalable platforms like Hugging Face Spaces, the solution offers an accessible, maintainable, and extensible framework suitable for educational platforms such as GUVI. 
This project highlights the practical applications of deep learning and multilingual NLP in enhancing user engagement and accessibility in digital learning environments.
Future work can include expanding the dataset to cover more languages, integrating voice-based interactions, and improving context retention for longer conversations.

#### Developer - B.LOGITHNATHAN
