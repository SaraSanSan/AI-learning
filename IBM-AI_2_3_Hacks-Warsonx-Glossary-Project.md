# | Generative AI: Prompt Engineering Basics |
# → PROMPT ENGINEERING: HACKS, WATSONX, PROJECT & WRAP-UP

This module includes a graded quiz to test and reinforce your understanding of concepts covered in the course. The module also includes a glossary to enhance comprehension of generative AI-related terms. The module includes a final project, which provides an opportunity to gain hands-on experience on the concepts covered in the course. The module also includes optional content. This content includes the techniques for writing effective prompts for image generation. Additionally, you can learn about Prompt Lab, a prompting tool designed to maximize your prompt engineering capabilities in IBM watsonx.

Learning Objectives:

    Apply prompt engineering techniques for writing effective prompts for image generation.
    Describe the user interface for Prompt Lab in IBM watsonx.
    Demonstrate understanding of the course concepts through the graded quiz and project.
    Plan for the next steps in your learning journey.



# PROMPT HACKS

- Objective

After completing this reading, you will be able to:

    Explain the concept of prompt hacks.
    Apply them to generate more effective outputs from generative AI models for text and image generation.
    Distinguish between text prompts and prompt engineering.

- Introduction

Prompt hacks in generative AI refer to techniques or strategies that involve manipulating the prompts or inputs provided to a generative AI model, such as a large language model (LLM) or an image generation model, to produce desired or specific outputs. These hacks include carefully crafting the prompts to influence the model's behavior and generate outputs that align with the user's intentions. 

They improve the performance of LLMs by:

1. Improving the quality and accuracy of LLM outputs: By carefully crafting the prompt, you can guide the LLM toward the desired output and reduce the likelihood of errors.

2. Enabling LLMs to perform new and innovative tasks: By combining prompts with other inputs, such as images or code, you can enable LLMs to perform tasks that they would not be able to perform otherwise.

3. Making LLMs more accessible and user-friendly: Using prompt hacks can make it easier for people to use LLMs easily and effectively.


### Prompt hacks and text-generation

Prompt hacks can be used with LLMs to generate more effective responses from text-generating generative AI models in the following ways:

1. Using special modifiers: LLMs have special modifiers that can control the style, tone, and other properties of the generated output. For example, you might use the modifier "write in a humorous style" to generate a funny poem or story.

2. Providing context and examples: The more context and examples you provide to the LLM, the better it will be able to understand what you want and generate the desired output. For example, if you wish the LLM to generate a code snippet for a specific task, you might provide it with a detailed description and some examples of similar code snippets.

3. Combining prompts with other inputs: Prompts can be combined with other inputs, such as images or code, to generate more complex and informative outputs. For example, you might prompt an LLM to generate a description of an image while providing it with the image itself.

Here's an EXAMPLE of using prompt hacks with text-generating models. 

You need a poem about a cat. So, you use the following prompt:

    Prompt: Write a poem about a cat.
    
    Output:
    
    A furry little creature,
    
    With four paws and a tail,
    
    It loves to chase mice,
    
    And play with its ball.

Now, this is a fairly straightforward poem about a cat. However, you require a slightly innovative output. You can use prompt hacking to bring in more creativity or humor. For example, you could add the following modifier to the prompt:

    Prompt: Write a poem about a cat in the style of a gangsta rapper.
    
    Output:
    
    Yo, I'm a cat, and I'm here to say,
    
    I'm the coolest cat around today.
    
    I got fur so soft and eyes so green,
    
    And I'm the best hunter you've ever seen.

You now have a poem, about a cat, which is creative and funny!

### Prompt hacks and image generation

Did you know you can use prompt hacking with LLMs to create images?

Directing image generation models through LLMs is an emerging method that is gaining popularity in artificial intelligence. This approach entails employing an LLM to guide an image generation model, like DALL-E 2 or Imagen, to produce more precise and lifelike images.

- How exactly does this work?

You provide the LLM with a text description of the image you want and then use the LLM's output to guide the image generation model.

For example, suppose you want to generate an image of a cat sitting on a couch. You could provide the LLM with a text prompt like this:

    Prompt: "A fluffy orange cat sitting on a red couch, looking at the camera."
    
    The LLM would then generate a response like this:
    
    Output:
    
    "A fluffy orange cat is sitting on a red couch. 
    It is looking directly at the camera. 
    Its eyes are green, and its fur is soft and smooth."

You can then use this response to guide the image generation model to generate an image of a cat sitting on a couch such that it matches the description provided by the LLM.

Here's another example. Imagine you need a background image for the poem "Twinkle twinkle little star."

You can use a prompt hack here and ask the LLM to suggest the prompt for generating this image.

    Prompt: Consider the poem "Twinkle twinkle little star." Can you create a text description of an image that represents this poem?
    
    Output: _The following image depicts the response generated by ChatGPT using this prompt._

The prompt hack comes after this. 

Prompt: Can you suggest a prompt that will be helpful to generate a relevant image for description: "In the serene backdrop of a dark velvet sky, a single radiant star takes center stage. The star glistens with a soft silver glow, casting a gentle, shimmering light onto the tranquil night landscape. The surrounding darkness is dotted with more distant stars, creating a celestial tapestry that seems to stretch forever. The star in focus stands out like a diamond in the sky, a beacon of hope and wonder. It symbolizes the innocence and curiosity of childhood, reminding us of the simple joys of looking up at the night sky and dreaming."
    
    Output: < Image >

Now, if you need to use the same prompt for DALL-E, you can also use a prompt hack here!

    Prompt: Can you rewrite the prompt for DALL-E?
    
    Output: < Image >

Bingo!

You now have what you want. You can use these images for the poem the way you'd like. 

### Prompt hacks and prompt engineering

Prompt hacking and prompt engineering are closely related fields, but they have some key differences.

Prompt hacking is the use of prompts to manipulate the output of an LLM in a way that is unexpected or unintended, whereas prompt engineering is the systematic design and development of prompts for LLMs

Prompt hacks VS Prompt engineering

- Purpose:
	To manipulate the output of an LLM in unexpected or unintended ways
    To improve the performance of an LLM on specific tasks.

- Approach:
	Experimental and creative
    Systematic and disciplined

- Application:
	Generating humorous or creative outputs
    Improving the performance of LLMs in machine translation, question answering, and other tasks

It is important to note that the distinction between prompt hacking and prompt engineering is not always clear-cut. Some techniques can be used for both purposes. For example, using special modifiers to control the style and tone of the output to generate humorous or creative outputs. It can also be used to improve the performance of an LLM on a specific task, such as generating text in a specific style.


### Tips for powerful prompt hacking

Here are some additional tips for prompt hacking:

    Be creative, and don't be afraid to try new things

    Be specific and clear in your instructions.

    Use the LLM's documentation to learn more about its capabilities and limitations.

    Experiment with different prompts and see what works best for you.

With some practice, you can use prompt hacking to generate high-quality and creative outputs from LLMs.

To conclude, prompt hacking is a powerful technique that can be used to get the most out of LLMs. However, it is a relatively new field, and there is no one-size-fits-all approach. The best way to learn how to hack prompts is to experiment and discover what works for you.

- Summary 

You learned the concept of prompt hacks in generative AI. You also learned how they can be used with LLMs for better text and image generation. Finally, you learned the difference between prompt hacking and prompt engineering. 



# Prompt Engineering using IBM WATSONX

In this optional lesson you will explore the Prompt Lab in IBM watsonx.ai. This is optional because it requires you to access IBM watsonx platform, which may not be available to everyone. Normally a credit card is required to access watsonx.ai. However, for learners in this course we are providing you with a feature code that will enable you to sign up without a credit card. 

To complete the lab you will need to perform the following:

	Obtain a feature code for an IBM Cloud account.
 	Create the IBM cloud account using the feature code.
  	Provision your instance for watsonx.ai and explore the Prompt Lab.

The next steps will be the following hands-on lab:

	Obtain IBM Cloud Feature Code and Activate Trial Account
	Creating an IBM Cloud Account
	Exploring watsonx Prompt Lab



# GLOSSARY

- API integration: Application programming interface integration refers to the process of connecting different software systems or applications through their APIs to enable them to work together and share data or functionality.

- Bias mitigation: A technique in which text prompts provide explicit instructions to generate neutral responses.

- Chain-of-Thought: An approach to prompt engineering that involves breaking down a complex task into smaller and easier ones through a sequence of more straightforward prompts.

- ChatGPT: A language model designed to provide detailed responses to natural language input.

- Claude: A powerful and flexible AI chatbot to help you with your tasks.

- Contextual guidance: A technique using which text prompts provide specific instructions to the LLMs to generate relevant output.

- DALL-E: Text-to-image model that generates digital images from natural language descriptions.

- Domain expertise: A technique wherein text prompts can use domain-specific terminology to generate content in specialized fields like medicine, law, or engineering, where accuracy and precision are crucial.

- Dust: A prompt engineering tool that provides a web user interface for writing prompts and chaining them together.

- Explainability: Refers to the degree to which a user can understand and interpret the model's decision-making process and the reasons behind its generated outputs.

- Few-shot prompting: A method that enables context learning, wherein demonstrations are provided in the prompt to steer the model to better performance.

- Framing: A technique by which text prompts guide LLMs to generate responses within the required boundaries.

- Generative AI: A type of artificial intelligence that can create new content, such as text, images, audio, and video.

- Generative AI models: Models that can understand the context of input content to generate new content. In general, they are used for automated content creation and interactive communication.

- GPT: Generative pre-trained transformers or GPT are a family of neural networks that uses transformer architecture to create human-like text or content as output.

- IBM watsonx.ai: A platform of integrated tools to train, tune, deploy, and manage foundation models easily.

- Integrated Development Environment (IDE): A software tool for crafting and executing prompts that engage with language models.

- Input data: Any piece of information provided as part of the prompt.

- Interview pattern approach: A prompt engineering strategy that involves designing prompts by simulating a conversation or interacting with the model in the style of an interview.

- LangChain: A Python library that provides functionalities for building and chaining prompts.

- Large language models (LLMs): A type of deep learning model trained on massive amounts of text data to learn the patterns and structures of language. They can perform language-related tasks, including text generation, translation, summarization, sentiment analysis, and more.

- Midjourney: A text-to-image model that generates images from natural language requests.

- Naive prompting: Asking queries from the model in the simplest possible manner.

- Natural language processing (NLP): A branch of artificial intelligence that enables computers to understand, manipulate, and generate human language (natural language).

- OpenAI Playground: A web-based tool that helps to experiment and test prompts with various models of OpenAI, such as GPT.

- Output indicator: Benchmarks for assessing the attributes of the output generated by the model.

- Prompt: Instructions or questions given to a generative AI model to generate new content.

- Prompt engineering: The process of designing effective prompts to generate better and desired responses.

- PromptBase: A marketplace for selling and buying prompts.

- Prompt lab: A tool that enables users to experiment with prompts based on different foundation models and build prompts based on their needs.

- PromptPerfect: A tool used to optimize prompts for different LLMs or text-to-image models.

- Role-play/Persona pattern: Specific format or structure for constructing prompts that involve the perspective of a character or persona.

- Scale AI: A technology company that specializes in data labeling and data annotation services.

- Stable Diffusion: A text-to-image model that generates detailed images based on text descriptions.

- StableLM: An open-source language model based on a dataset that contains trillions of tokens of content.

- Tree-of-Thought: An approach to prompt engineering that involves hierarchically structuring a prompt or query, akin to a tree structure, to specify the desired line of thinking or reasoning for the model.

- User feedback loop: A technique wherein users provide feedback to text prompts and iteratively refine them based on the response generated by the LLM.

- Zero-shot prompting: A method using which generative AI models generate meaningful responses to prompts without needing prior training on those specific prompts.



# FINAL PROJECT: Applying Prompt Engineering Techniques and Best Practices


# WRAP-UP

Congratulations on successfully completing this course! We hope you found it enriching.

In this course, you learned about prompts and prompt engineering in generative AI. You learned that writing effective prompts involves four key dimensions: clarity, context, precision, and role-play.

You explored common prompt-engineering tools like IBM watsonx Prompt Lab, Spellbook, Dust, and PromptPerfect.

You gained knowledge of text-prompt techniques like zero-shot and few-shot, which improve the reliability and quality of large language models (LLMs).

You were also introduced to various prompt engineering approaches: Interview Pattern, Chain-of-Thought, and Tree-of-Thought.

This foundational knowledge of prompt engineering will enable you to effectively utilize the capabilities of generative AI to produce precise and relevant responses.

This concludes the Generative AI: Prompt Engineering course. However, it only marks a milestone in your ongoing journey to delve deeper into the world of generative AI.
