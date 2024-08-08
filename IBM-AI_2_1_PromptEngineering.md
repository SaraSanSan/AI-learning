# | Generative AI: Prompt Engineering Basics |
# → PROMPT ENGINEERING FOR GENERATIVE AI

In this module, you will learn the concept of prompt engineering in generative AI. You will also learn the best practices for writing effective prompts and assess common prompt engineering tools.

Learning Objectives:

    Assess commonly used tools for prompt engineering.
    Define a prompt and its elements.
    Explain the concept and relevance of prompt engineering in generative AI.
    Apply the best practices for writing effective prompts to obtain the desired response.
    Explore commonly used tools for prompt engineering.


# WELCOME TO THE COURSE

## Course Introduction

Let's get started with the Basics of Prompt Engineering.
An expert knows all the answers if you ask the right questions.
Interestingly, this is the same principle on which we design prompts for
generative AI models, prompts that we use to query and question AI applications such
as chatbots, image, audio or video generation tools, and even virtual worlds.
Prompts optimize the response of generative AI models.
The power lies in the questions that you ask.
Knowing how to write a prompt that is effective and
direct will allow you to generate more precise and relevant content.
A good question to ask right now is what will I be able to do after completing this
course?
This course invites all beginners, whether professionals, enthusiasts, practitioners,
or students who have a genuine interest in learning how to write effective prompts.
A course for everyone regardless of your background or experience.
By the end of this course, you'll be able to explain the concept and relevance of
prompt engineering in generative AI models, apply the best practices for
creating prompts, assess commonly used tools for prompt engineering, and apply
common prompt engineering techniques and approaches for writing effective prompts.
This is a focused course comprising three modules,
each of which requires one to two hours to complete.
In Module 1 of the course, you'll learn about the concept of prompt engineering,
starting with how to define a prompt and its elements.
You'll learn to apply the best practices for writing effective prompts,
and assess common prompt engineering tools such as IBM watsonx, Prompt Lab,
Spellbook, and Dust.
In Module 2, you'll study various prompt engineering approaches like
Interview Pattern, Chain-of-Thought, and Tree-of-Thought.
You'll discover techniques for skillfully crafting prompts such as Zero -shot and
Few-shot to produce precise and relevant responses.
Module 3 requests your participation in a final project and
presents a graded quiz to test your understanding of course concepts.
You can also visit the course glossary and
receive guidance on the next steps in your learning journey.
The course is curated with a mix of concept videos and supported readings.
Watch all the videos to capture the full potential of the learning material.
You'll enjoy hands on labs and a final project that demonstrates how to optimize
results by creating effective prompts in the IBM generative AI classroom.
The course includes practice quizzes to help you reinforce your learning.
At the end of the course, you'll also attempt a graded quiz.
The course also offers discussion forums to connect with the course staff and
interact with your peers.
Most interestingly, through the Expert viewpoint videos, you'll hear
from experienced practitioners who will share their perspectives on the tools and
approaches used in prompt engineering and the art of writing effective prompts.
Are you ready to learn everything you can about writing prompts to unlock the full
potential of generative AI?


## Course Overview

This course is designed for practitioners and enthusiasts passionate about learning prompt engineering techniques to unlock the full potential of generative artificial intelligence (AI) models.

This course explains the techniques, approaches, and best practices for writing effective prompts. You will learn to utilize these techniques to effectively guide generative AI models and control their output to obtain the desired results.

You will learn about prompt techniques like zero-shot and few-shot, which can improve the reliability and quality of large language models (LLMs).You will also explore various prompt engineering approaches like Interview Pattern, Chain-of-Thought, and Tree-of-Thought, which aim at generating precise and relevant responses.

You will be introduced to commonly used prompt engineering tools like IBM watsonx Prompt Lab, Spellbook, and Dust. 

The hands-on labs included in the course offer an opportunity to optimize results by creating effective prompts in the IBM Generative AI Classroom. You will also hear from practitioners about the tools and approaches used in prompt engineering and the art of writing effective prompts.

After completing this course, you will be able to:

    Explain the concept and relevance of prompt engineering in Generative AI models

    Assess commonly used tools for prompt engineering

    Apply best practices for writing effective prompts

    Apply common prompt engineering techniques and approaches for writing prompts

- Course Content

This course is divided into three modules. It is recommended that you complete one module per week or at a pace that suits you - whether its a few hours every day, or completing the entire course over a weekend or even in one day.

1. Week 1 - Module 1: Prompt Engineering for Generative AI

In this module, you will learn the concept of prompt engineering in generative AI. You will also learn the best practices for writing effective prompts and assess common prompt engineering tools.

2. Week 2 - Module 2: Prompt Engineering: Techniques and Approaches

In this module, you will discover techniques to craft prompts that effectively steer generative AI models. You will also learn about various prompt engineering approaches that can enhance the capabilities of generative AI models to produce precise and relevant responses.

3. Week 3 - Module 3: Course Quiz and Wrap-Up

In this module, you will attempt a graded quiz that will test and reinforce your understanding of the concepts covered in the course. The module also includes a glossary to enhance your comprehension of generative AI-related terms. Finally, this module will guide you toward the next steps in your learning journey.

This module also includes optional topics related to text-to-image prompting and prompt engineering capabilities in IBM watsonx. 

- Learning Resources

The course offers a variety of learning assets: videos, readings, hands-on labs, expert viewpoints, discussion prompts, and quizzes.

The concepts are presented through videos and readings, complemented by hands-on learning experiences in the labs.

Expert Viewpoints are videos that feature industry practitioners showcasing real-world applications of the skills taught in this course.

Interactive learning is encouraged through discussions where you can meet your staff and peers.

Practice quizzes at the end of each module will test your understanding of what you learned. The final graded quiz will assess your conceptual understanding of the course.

- Who Should Take This Course?

This course caters to any one eager to delve into the concept of prompt engineering and explore the various tools and approaches. 

This course is for you if you are: 

1. An individual looking for an introduction to prompt engineering

2. A student aiming to graduate with practical knowledge of writing effective prompts for generative AI models, thereby increasing job readiness

3. A professional seeking to enhance your professional capabilities and efficiency by leveraging the capabilities of prompt engineering in generative AI

4. A manager or executive keen on using prompt engineering for strategic advantages in your organization

- Recommended Background

This course is relevant for anyone interested in exploring the field of generative AI and requires no specific prerequisites.

The course uses simple, easy-to-understand language to explain the critical concepts of generative AI without relying on technical jargon. The hands-on labs provide an opportunity to practice the skills covered in the course and do not require a programming background or college degree.

To derive maximum learning from this course, all that’s needed is active participation in and completion of the various learning engagements offered throughout the modules.

Good luck!



# CONCEPT OF PROMPT ENGINEERING

## What Is a Prompt? 

Welcome to "What Is a Prompt?"
After watching this video,
you will be able to define a prompt and its elements.
You will also be able to explain the relevance of writing
effective prompts to guide
generative AI models to produce the desired results.
One of the significant capabilities of
generative AI models is that
their output closely resembles what a human can produce.
Relevant, contextual, imaginative, nuanced,
and linguistically accurate and one of
the critical factors in generating this output is prompt.
What is a prompt? A prompt is any input you
provide to a generative model
to produce a desired output.
You can think of it as an instruction
you provide to the model.
For example, write a small paragraph
describing your favorite holiday destination.
Write HTML code to generate
a dropdown selection of cities within an online form.
These are straightforward prompts
used to produce a specific output.
Prompts can also be a series of instructions that refine
the output step by step to achieve the desired result.
For example, write a short story
about a scientist studying life on Mars.
What were some of the challenges
he faced during his research?
With these examples, it is
clear that prompts contain questions,
contextual text, guiding patterns or examples,
and partial input for the model.
Based on these natural language requests
submitted as prompts,
generative AI models collect information,
derive inferences, and provide creative solutions.
These instructions help the model produce
relevant and logical responses
or output based on provided inputs.
Let's look at some more examples
to help us understand this better.
Suppose you want the model to write
a short story about the struggles and
achievements of a farmer who became
a successful businessman in 10 years.
If your prompt is rich man's story from a small town,
his struggles and achievements,
it'll produce a generic output.
As this is what we call naive prompting.
It means asking queries from
the model in the simplest possible manner.
To convey your intentions to the model,
you can make simple adjustments
that can radically improve the result.
Like your prompt must have context to
proper structure and can be comprehensible so
you can rewrite the prompt as
"Write a short story about the struggles and
achievements of a farmer who became
a rich and influential businessman in 10 years."
Let's look at another example where you want the model to
generate an image of a sunset scenery you have in mind.
Writing the prompt as "Sunset image
between mountains" may not give you the desired output.
The prompt is too brief and lacks
a detailed outline of the image you have in mind.
You can rewrite the prompt as "Generate an image
depicting a calm sunset about
a river valley that rests amidst the mountains."
To master the art of writing effective prompts,
let's understand the building blocks of a
well constructed prompt one by one.
Instructions, give the model
distinct guidelines regarding the task
you wish to execute.
Steering the actions of
the generative AI model to
influence the formation of its response.
Like "Write an essay in 600 words,
analyzing the effects of
global warming on marine life" is one example.
Context, helps establish
the circumstances that form the setting of
the instruction and provides
a framework for generating relevant content.
To understand this, let's add some context
to the prompt discussed in the previous example.
"In recent decades, global warming
has undergone significant shifts,
leading to rising sea levels,
increased storm intensity, and changing weather patterns.
These changes have had a severe impact on marine life.
Write an essay in 600 words
analyzing the effects of global warming on marine life."
This prompt will help the model generate
output aligned with the context.
Input data is any piece of
information provided by you as part of the prompt.
This can be used as a reference
for the generative model to
attain responses with a specific set of details or ideas.
To provide input data,
the same prompt can be
reconstructed in the following manner.
"You have been provided with a data set containing
temperature records and measurements
of sea levels in the Pacific Ocean.
Write essay in 600 words,
analyzing the effects of
global warming on marine life in the Pacific Ocean."
Output indicator, offers benchmarks for
assessing the attributes of
the output generated by the model.
It can outline the tone, style,
length, and other qualities you desire from the output.
In the prompt "Write an essay in 600 words,
analyzing the effects of global warming on marine life,"
the output indicator specifies that
the output generated should be an essay of 600 words.
It will be evaluated based on the clarity of
the analysis and the incorporation
of relevant data or case studies.
Each of these elements plays a role in helping
the generative AI model comprehend
your requirements and give you the desired output.
In this video, you learned that a prompt is
any input or series of instructions you
provide to a generative model
to produce a desired output.
These instructions help in directing the creativity of
the model and assist it in
producing relevant and logical responses.
The building blocks of a well
structured prompt include instruction,
context, input data, and output indicators.
These elements help the model comprehend
our necessities and generate relevant responses. 


## What Is Prompt Engineering? 

Welcome to What is Prompt Engineering?
After watching this video,
you'll be able to define what
prompt engineering is and explain the relevance and
importance of prompt engineering
with respect to generative AI models.
You'll also be able to explain
the process involved in formulating
effective prompts through prompt engineering
to guide these models to produce relevant responses.
The process of designing effective prompts to generate
better and desired responses
is called prompt engineering.
Although generative AI models have
the potential to supplement human creativity,
if you fail to provide precise prompts,
these models may produce
inadequate results and even
false and misleading information.
Prompt engineering is a blend of critical analysis,
creativity, and technical acumen.
It is not limited to asking the right question.
It includes framing the question in
the right context with the right information
and your expectation of
desired outcomes to elicit the most appropriate response.
Let's understand this through an example.
A ship is sailing through the Atlantic Ocean.
To plan his voyage, the ship's captain wants to know
the precise weather forecast for
a specific location at a specific time.
In this case, providing the model with a simple prompt,
such as weather forecast of the Atlantic Ocean,
may not get the desired results.
To get the most accurate results,
the captain will have to engineer the prompts.
When designing the prompt, the captain needs to
define the context to include details such
as the intended location for the weather forecast
in latitude and longitude
and the time range for prediction.
For example, the captain of a ship is
planning a strategic voyage in the Atlantic Ocean.
To help the captain navigate effectively,
provide weather forecasts for the upcoming week from
28th August 2023 to 1st September 2023.
The coordinates of the target location
are between 20 degrees north and
30 degrees north latitude and
40 degrees west and 20 degrees west longitude.
The captain must also indicate
whether he requires specific output,
like should the model return information on
other weather elements that could affect the voyage.
For example, to help plan
an effective navigation in the Atlantic Ocean,
provide detailed information about
expected wind patterns, wave heights,
precipitation probabilities, cloud cover,
and any potential storms that might affect
the voyage during a specified time frame and location.
It's important to recognize that prompt engineering is
a well-structured iterative process that involves
refining the prompts and experimenting with
various factors that could
influence the output from the model.
Let's understand the step-by-step
process involved in creating
effective prompts through
prompt engineering. Define the goal.
The initial step in the process
involves establishing a distinct goal.
You must know what exactly
you want the model to generate.
For example, form a brief overview of the benefits and
risks associated with
artificial intelligence and automobiles.
Craft initial prompt.
Having defined the goal,
it's now time to create an initial prompt.
This might manifest as a question,
a directive, or even a situation depending on the goal.
For example, write an article that presents
a well-rounded analysis of the benefits and drawbacks
associated with the incorporation of
artificial intelligence in
the field of automobile industry.
Test the prompt. The prompt you created
should now be tested and analyzed for its response.
While the response might be relevant,
it could lack the distinct
perspective you are aiming for.
For example, the response to
the initial prompt directly lays out the benefits and
drawbacks of integrating artificial intelligence
in the automobile industry.
It does not highlight any
ethical concerns that might arise.
Further, there's no discussion on
the positive and negative implications of the scene.
Analyze the response, you must carefully
review the response and examine
whether it aligns with your goals.
If not, make a note of the areas where it fell short.
For example, the initial prompt used fails to
cover a comprehensive range of benefits and risks
associated with artificial intelligence
in the automobile industry. Refine the prompt.
Using the knowledge acquired
through testing and analysis,
it's now appropriate to modify the prompt.
This might include enhancing its specificity,
incorporating additional context, or rephrasing.
The initial prompt can be refined as follows.
Write an informative article discussing the role of
artificial intelligence in
revolutionizing the automobile industry.
Address key aspects such as benefits, drawbacks,
ethical considerations,
and both positive and negative implications.
Cover specific domains like
autonomous driving and real-time traffic analysis,
while also examining potential challenges such as
technical complexity and cybersecurity concerns.
Iterate the process. The last three steps
are repeated until you're satisfied with the response.
Consequently, following several cycles of refinement,
the final prompt shall take this form
: Write an article highlighting how
artificial intelligence is reshaping
the automobile industry focusing
on the positive advancements,
particularly in autonomous driving
and real-time traffic analysis,
while thoroughly exploring concerns related to
intricate technical aspects such as
decision-making algorithms and
potential cybersecurity breaches.
Emphasize the implications these concerns
may have on vehicle safety.
Ensure that the analysis is thorough,
backed with examples, and encourages critical thinking.
Now let's summarize the importance and relevance of
prompt engineering and generative AI models.
Optimizing model efficiency.
Prompt engineering helps design
intelligent prompts that allow the users to harness
the full capabilities of
these models without requiring extensive retraining.
Boosting performance for specific tasks.
Prompt engineering empowers generative AI models
to deliver responses that are nuanced and have a context,
rendering them more effective for specific tasks.
Understanding model constraints.
Refining prompts through each iteration and studying
the corresponding responses of the model
can help us understand its strengths and weaknesses.
This knowledge can further guide
feature enhancement or complete development
of the model in the future.
Enhancing model security.
Skilled prompt engineering can prevent issues of
harmful content generation due
to poorly designed prompts,
thereby enhancing safe utilization of the model.
In this video, you learned that
prompt engineering is the process
of designing effective prompts
to leverage the full capabilities of
generative AI models and producing optimal responses.
You also learned the process of
refining a prompt via prompt engineering.
At last, you learned the importance of
prompt engineering and optimizing model efficiency,
boosting performance, understanding model constraints,
and enhancing its security. 


### Hands on Lab: Getting to Know Our AI Prompting Tool

### Hands on Lab: Experimenting with Prompts


## Best Practices for Prompt Creation

Welcome to best practices for prompt creation.
After watching this video,
you will learn to apply the best practices
for creating effective prompts
and explain the process of drafting
and refining prompts through various examples.
Writing effective prompts is
crucial for utilizing the full potential of
generative AI models to
produce relevant and accurate responses.
By applying the best practices
for creating effective prompts,
you can supervise the style,
tone, and content of the output generated.
You can apply the best practices for crafting
effective prompts across four essential dimensions:
clarity, context, precision,
and role play or persona pattern.
Let's explore each of these aspects individually.
To have clarity in your prompt,
keep the following points in mind.
Simple and straightforward language
can convey instructions easily.
Write prompts that are unambiguous
and easy to comprehend.
Specialized terminologies can potentially
puzzle the model or the users,
so write prompts using simple terms that
can be understood by a broad range of audiences.
Vague prompts could lead to responses
that do not align with your intentions,
therefore, you must provide
a clear description of
the task that the model must perform.
Let's understand this through an example.
Discuss culinary processes that take place on
foliaceous stipules of plants with the help of sunlight,
also mention a green thing and how light, air,
and water are important for aerial parts of the plant.
This prompt has much ambiguity.
Nowhere does it explicitly
mention the process you want to discuss.
The prompt contains complex terminologies
which make it difficult to comprehend.
It's also vague and does not
clearly describe the task at hand.
To ensure clarity, you can rewrite this prompt as,
explain the process of photosynthesis in plants,
detailing the role of chlorophyll and how sunlight,
carbon dioxide, and water
contribute to this biological function.
The revised prompt has simple, clear,
and concise language and explicitly states that
you want to discuss the process
of photosynthesis in plants.
Moving on to the next essential dimension,
which is the context.
Context always helps the model
understand the situation or the subject.
This could involve giving a brief introduction or
explanation of the circumstances
in which the response is required,
relevant information or specific details like people,
places, events, or concepts
help guide the understanding of the model.
It's important to incorporate
such details while writing prompts.
For example, the prompt,
write what happened during the outbreak of
the Revolutionary War in 1775 does
not contain adequate context and
specific details to guide the understanding of the model.
To establish the right context and
include the relevant information,
you can rewrite this prompt as, describe
the historical events leading to
the American Revolutionary War,
focusing on key incidents like the Boston Tea Party,
Battle of Saratoga and so on.
Highlight the tensions between
the American colonies and
the British government and explain
how these events led to the outbreak of
the Revolutionary War in 1775.
Another important dimension for
creating effective prompts is precision.
Precision helps outline your request in the prompt.
If you're searching for a particular kind of response,
express that with clarity.
Examples incorporated
within your prompts can help the model
understand what kind of response you're
looking for and direct its thought process.
For example, in the prompt talk about supply
and demand and how it is affected in economics,
there's no precise outline of
a particular kind of response and no examples.
To ensure precision, you can rewrite this prompt
as explain the concept
of supply and demand in economics,
describe how an increase in
demand can influence pricing with
the help of an illustrative example
like the smartphone market.
Similarly, explain the repercussions
of reduced supply on pricing by
drawing parallels with situations
like disruptions in oil production.
This prompt clearly expresses that you
want to explain a concept with the help of examples.
Finally, let's discuss the last dimension,
which is role play or persona pattern.
Prompts written from the perspective
of a specific character or
persona can help the model
generate responses aligned with that perspective.
Essential contextual details enable
the model to effectively assume a particular role.
If you're requesting the model to reply
from the standpoint of a historical figure,
a fictional character or a specific profession,
then provide contextual details.
Let's look at this example here.
Write a log entry describing
the strange flora and fauna of an uncharted alien planet.
This prompt will simply give scientific details about
the alien planet and will not explain
its answer from the perspective of a professional.
You can rewrite the prompt as pretend you are
an astronaut who has just landed
on an uncharted alien planet.
Write a log entry describing
the strange flora and fauna you've encountered,
like the color of the sky and
the unfamiliar sounds echoing
through the alien landscape.
Express your feelings of excitement, curiosity,
and a hint of apprehension as you
document this extraordinary journey.
In this example, you explicitly gave
contextual details and assumed
yourself to be an astronaut.
This prompt will generate a response
aligned with the perspective of an astronaut.
In this video, you learned
that writing effective prompts for
generative AI models is
essential for supervising the style,
tone, and content of the output.
Best practices for writing
effective prompts can be implemented
across four dimensions:
clarity, context, precision, and role play.
Clarity includes using simple and concise language,
context provides background and required details,
precision means being specific and providing examples.
Role play can enhance responses by assuming
a persona and offering relevant context.
These practices can be adapted to
specific needs for optimal results. 


### Hands on Lab: Naive Prompting and Persona Pattern


## Common Prompt Engineering Tools

Welcome to Common Prompt Engineering Tools.
After watching this video,
you'll be able to describe the common functionalities of
prompt engineering tools and explain
the capabilities of a few
common tools for prompt engineering.
Prompt engineering is the process of designing
accurate and contextually
appropriate prompts to interact with
generative AI models to
generate relevant and accurate outputs.
To aid you with this process,
you have diverse prompt engineering tools.
Prompt engineering tools provide various features and
functionalities to optimize the creation
of prompts for desired outcomes.
These tools are specifically
useful for users who may not be
proficient with natural language processing
or NLP techniques,
but want to achieve specific outcomes
when using generative AI models.
Let's explore the common functionalities
offered by diverse prompt engineering tools.
Firstly, several tools for
prompt engineering offer suggestions for prompts
based on a given input or the desired output.
Next, these tools can suggest
how to structure prompts
for better contextual communication.
They help craft prompts that provide
the necessary context for
the model to understand the user's intent.
You can iteratively refine prompts based on
the initial responses from
a tool to find the most effective prompt.
Prompt engineering tools might offer features to help
mitigate bias in the response of a generative AI model.
They can guide how to craft prompts to reduce
the likelihood of biased or inappropriate outputs.
These tools can help create prompts relevant to
specific domains such as legal, medical, or technical.
Some prompt engineering tools offer libraries of
predefined prompts for various use cases
that can be customized for specific needs.
Moving forward, let's explore
a few common tools for prompt engineering.
Let's start with IBM Watsonx.ai.
A platform of integrated tools to train,
tune, deploy, and manage foundation models easily.
The platform includes the Prompt Lab tool
that enables users to experiment with
prompts based on different foundation models
and build prompts based on their needs.
To help you get started,
Prompt Lab provides sample prompts
for different use cases,
including summarization,
classification, generation, and extraction.
To create prompts specific to your needs,
you can train a model by adding instructions and
examples to show the model how to respond to the input.
Moving further, let's learn about Spellbook.
An integrated development environment,
or IDE by Scale AI.
With Spellbook, you can build applications
based on a language model or LLM,
and experiment with prompts for
various use cases including text generation,
text extraction, classification, question answering,
auto completion, and summarization.
For prompt engineering, Spellbook includes
a prompt editor that enables
you to edit and test prompts.
You can use prompt templates to
leverage structured prompts for generating text.
You can also access pre-built prompts as examples.
Another tool for prompt engineering is Dust.
It provides a web user interface
for writing prompts and chaining them together.
You can manage different versions of chain prompts.
It also provides a custom coding language in a set of
standard blocks for processing
the outputs provided by the LLMs.
Dust also supports API integration
to integrate other models and services.
Another tool for effective
prompt engineering is PromptPerfect,
which can be used to optimize prompts for
different LLMs or text to image models.
It supports common text models such as GPT, Claude,
StableLM, and Llama,
and image models such as DALL-E and Stable Diffusion.
For writing or optimizing a prompt,
you first need to select
the relevant model for which you
want to optimize the prompt.
Different models have different optimizing strategies.
You can also select the add-ons related to preview,
quality, language, and moderation.
When you write a prompt, you can experiment with
the autocomplete feature that
provides suggestions as you type.
You can further optimize the written prompt.
Here you can see an example that
reveals the original prompt written by
a user and the corresponding optimized prompt
generated by PromptPerfect.
For a further level of optimization,
you can optimize and refine
the prompt step by step in the streamline mode.
You write a prompt, optimize it,
and again edit the prompt and
optimize until you are satisfied with the output.
Some other popular tools and
interfaces provide resources for
prompt engineering or help you experiment with prompts.
GitHub provides vast repositories
for prompt engineering and LLMs.
The guides, examples, and tools provided in
these repositories help
improve prompt engineering skills.
OpenAI Playground is a web based tool
that helps to experiment and
test prompts with various models of OpenAI such as GPT.
Playground AI platform helps you experiment with
text prompts for generating images
with the Stable Diffusion model.
LangChain is a Python library that
provides functionalities
for building and chaining prompts.
Finally, it's interesting to learn that
prompts are also available for buying and selling.
One such example of a marketplace
for prompts is PromptBase.
PromptBase supports prompts for
popular generative AI tools and models,
including Midjourney, ChatGPT,
DALL-E, Stable Diffusion, and Llama.
Through PromptBase, you can buy prompts
specific to your requirements
and specific to a model or tool.
For example, you can buy a prompt to generate
comical cartoon characters through Midjourney.
Also, if you have good prompt crafting skills,
you can upload and sell prompts through PromptBase.
It also supports crafting prompts directly
on the platform and selling them on its marketplace.
In this video, you learned that prompt engineering tools
provide various features and
functionalities to optimize prompts.
Some of these functionalities include
suggestions for prompts, contextual understanding,
iterative refinement, bias mitigation,
domain-specific aid, and libraries of predefined prompts.
A few common tools and platforms for
prompt engineering include IBM Watsonx.ai,
Prompt Lab, Spellbook, Dust, and PromptPerfect. 



# LESSON SUMMARY MODULE 1

At this point, you have learned the concepts of prompts and prompt engineering in generative AI. You have also explored the best practices for writing effective prompts and some common prompt engineering tools.

You learned the definition of prompts and their elements. You were introduced to prompt engineering and its relevance to generative AI models. You learned the best practices for writing effective prompts and how to refine them. You learned the functionalities and capabilities of common prompt engineering tools. You even got the opportunity to experience creating prompts and learning about naive prompting and persona patterns through hands-on lab experiences. You were privy to what experts from the field had to say about prompt engineering. 

Specifically, you learned that:

- A prompt is any input or a series of instructions you provide to a generative model to produce a desired output.

- These instructions help in directing the creativity of the model and assist it in producing relevant and logical responses. 

- The building blocks of a well-structured prompt include instruction, context, input data, and output indicators. 

- These elements help the model comprehend our necessities and generate relevant responses. 

- Prompt engineering is designing effective prompts to leverage the full capabilities of the generative AI models in producing optimal responses.

- Refining a prompt involves experimenting with various factors that could influence the output from the model.

- Prompt engineering helps optimize model efficiency, boost performance, understand model constraints, and enhance its security.

- Writing effective prompts is essential for supervising the style, tone, and content of output.

- Best practices for writing effective prompts can be implemented across four dimensions: clarity, context, precision, and role-play.

- Prompt engineering tools provide various features and functionalities to optimize prompts. 

- Some of these functionalities include suggestions for prompts, contextual understanding, iterative refinement, bias mitigation, domain-specific aid, and libraries of predefined prompts. 

- A few common tools and platforms for prompt engineering include IBM watsonx Prompt Lab, Spellbook, Dust, and PromptPerfect.
- 
