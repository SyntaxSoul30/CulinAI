# CulinAI 🍳

CulinAI is a state-of-the-art Generative AI content platform that simplifies the cooking experience. By leveraging **Spring Boot 3** and **Spring AI**, the application provides a unified interface for generating both text-based culinary instructions and high-quality visual representations of dishes. 

## 🚀 Features

* **Recipe Generation**: Utilizes OpenAI's **GPT-4o** to create structured, creative recipes with integrated context-aware ingredient substitution based on user prompts.
* **AI Image Synthesis**: Integrated with **DALL-E 3** to generate photorealistic imagery of the final dish.
* **Modular Service Architecture**: Decoupled logic into specialized `ImageService`, `RecipeService`, and `ChatService` for high maintainability.
* **Responsive UI**: A modern **React** frontend that facilitates real-time, asynchronous content generation.

## 🛠️ Tech Stack

* **Backend**: Java 17+, Spring Boot 3.4+, Spring AI 
* **AI Models**: OpenAI GPT-4o, OpenAI DALL-E 3 
* **Frontend**: React, Tailwind CSS
* **Build Tool**: Maven 

## 🏗️ System Architecture



## ⚙️ Configuration

Ensure you have your OpenAI API key set in your environment variables or `application.properties`:

```properties
spring.ai.openai.api-key=${OPENAI_API_KEY}
spring.ai.openai.image.options.model=dall-e-3
