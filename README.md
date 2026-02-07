# CulinAI 🍳

CulinAI is a state-of-the-art Generative AI content platform that simplifies the cooking experience. [cite_start]By leveraging **Spring Boot 3** and **Spring AI**, the application provides a unified interface for generating both text-based culinary instructions and high-quality visual representations of dishes. 

## 🚀 Features

* [cite_start]**Recipe Generation**: Utilizes OpenAI's **GPT-4o** to create structured, creative recipes based on user prompts. [cite: 28]
* [cite_start]**AI Image Synthesis**: Integrated with **DALL-E 3** to generate photorealistic imagery of the final dish. [cite: 28, 30]
* [cite_start]**Modular Service Architecture**: Decoupled logic into specialized `ImageService`, `RecipeService`, and `ChatService` for high maintainability. [cite: 29]
* [cite_start]**Responsive UI**: A modern **React** frontend that facilitates real-time, asynchronous content generation. [cite: 30]

## 🛠️ Tech Stack

* [cite_start]**Backend**: Java 17+, Spring Boot 3.4+, Spring AI [cite: 28]
* [cite_start]**AI Models**: OpenAI GPT-4o, OpenAI DALL-E 3 [cite: 28]
* [cite_start]**Frontend**: React, Tailwind CSS [cite: 30]
* [cite_start]**Build Tool**: Maven 

## 🏗️ System Architecture



## ⚙️ Configuration

Ensure you have your OpenAI API key set in your environment variables or `application.properties`:

```properties
spring.ai.openai.api-key=${OPENAI_API_KEY}
spring.ai.openai.image.options.model=dall-e-3
