# | DISCOVER THE ART OF PROMPT ENGINEERING |

Write effective prompts to get the output you want. Learn how to incorporate prompting techniques, such as few-shot prompting, into your work. Understand how generative AI tools produce output and the importance of evaluating output before using it. By the end of this module, you will be able to write clear and specific prompts and produce outputs that help accomplish workplace tasks.

Learning Objectives:

    Explain potential issues in LLM output.
    Describe the role of writing effective prompts in producing LLM output.
    Create prompts that provide clear and specific instructions for a variety of use cases relevant to knowledge workers.
    Analyze the output of an LLM model and refine prompts as needed.
    Apply specific prompting techniques, including few-shot prompting.


# LARGE LANGUAGE MODELS AND THEIR OUTPUT

## Module 3 introduction: Discover the art of prompt engineering

Prompt engineering involves designing
the best prompt you can to get the output you want.
Think about how you use language in your daily life.
Language is used for so many purposes:
to build connections, express opinions, or explain ideas.
And sometimes, you might wanna use language
to prompt others to respond in a particular way.
Maybe you want someone to give you a recommendation
or clarify something.
In those cases, the way you phrase your words
can affect how others respond.
The same is true when prompting a conversational AI tool
with a question or request.
A prompt is text input that provides instructions
to the AI model on how to generate output.
For example, someone who owns a clothing store
might want an AI model to output new ideas
for how to market their clothing.
This business owner might write the prompt:
"I own a clothing store.
We sell high fashion womenswear.
Help me brainstorm marketing ideas."
In this section of the course,
you'll focus on how to design or engineer effective prompts
to achieve more useful results
from a conversational AI tool.
My name is Yufeng, and I'm an engineer at Google.
I first became interested in prompting
because getting useful responses from language models
was time-consuming.
Sometimes it was even quicker for us to do the work
without the use of AI.
I was inspired to help our tools
be more efficient, not less.
I'm excited to help you learn more
about developing effective prompts.
First, you'll discover how LLMs generate output
in response to prompts.
And then, you'll explore the role of prompt engineering
in improving the quality of the output.
Prompt engineering is the practice
of developing effective prompts that elicit useful output
from generative AI.
You'll learn to create clear and specific prompts,
one of the most important parts of prompt engineering.
The more clear and specific your prompt,
the more likely you are to get useful output.
Another important part of prompt engineering is iteration.
You'll learn about evaluating output
and revising your prompts.
This will also help you get the results you need
when leveraging conversational AI tools in the workplace.
We'll also explore a specific prompting technique
called few-shot prompting.
Writing effective prompts involves
critical thinking and creativity.
It can also be a fun process,
and it's a very important skill to practice
if you wanna use AI effectively in the workplace.
Are you excited to get started on prompt engineering?
Let's go. 


## Understand large language models

It's helpful to understand how LLMs work
and to be aware of their limitations.
A large language model, or LLM,
is an AI model that is trained on large amounts
of text to identify patterns between words, concepts,
and phrases, so that it can generate responses to prompts.
So how do LLMs learn
to generate useful responses to prompts?
An LLM is trained on millions of sources of text,
including books, articles, websites, and more.
This training helps the model learn the patterns
and relationships that exist in human language.
In general, the more high quality data the model receives,
the better its performance will be.
Because LLMs can identify so many patterns in language,
they can also predict what word is most likely to come next
in a sequence of words.
Consider a simple example to get a basic understanding
of how LLMs predict the next word in a sequence.
Take the incomplete sentence,
"After it rained, the street was..."
An LLM can predict what word comes next
by computing the probabilities for different possible words.
Based on the available data,
the word wet might have a high probability
of being the next word.
The word clean, a lower probability.
And the word dry, an extremely low probability.
In this case, the LLM might complete the sentence
by inserting the word with the highest probability
of coming next in the sequence, wet.
Or it might be another high probability word like damp.
An LLM may vary in its response
to the same prompt each time you use it.
LLMs use statistics to analyze the relationships
between all the words in a given sequence
and compute the probabilities for thousands
of possible words to come next in that sequence.
This predictive power enables LLMs to respond to questions
and requests, whether the prompt is
to complete a simple sentence
or to develop a compelling story
for a new product launch or ad campaign.
Although LLMs are powerful,
you may not always get the output you want.
Sometimes this is because of limitations
in an LLM's training data.
For instance, an LLMs output may be biased
because the data it was trained on contains bias.
This data may include news articles
and websites that reflect
the unfair biases present in society.
For example, because of the data it was trained on,
an LLM may be more likely to produce output
that associates a professional occupation
with a specific gender role.
The training data that informs an LLM
can be limited in other ways as well.
For instance, an LLM might not generate sufficient content
about a specific domain or topic
because the data it was trained on
does not contain enough information about that topic.
Another factor that can affect output is the tendency
of LLMs to hallucinate.
Hallucinations are AI outputs that are not true.
While LLMs are good at responding to many kinds of questions
and instructions, they can sometimes generate text
that is factually inaccurate.
Let's say you're researching a company
and you use an LLM
to help you summarize the company's history.
The LLM might hallucinate
and provide incorrect information about certain details
such as the date the company was founded
or the current number of employees.
A number of factors can contribute to hallucinations,
such as the quality of an LLM's training data,
the phrasing of the prompt,
or the method an LLM uses to analyze text
and predict the next word in a sequence.
Because of an LLM's limitations, it's important
that you critically evaluate all LLM output
to determine if it is factually accurate, is unbiased,
is relevant to your specific request,
and provides sufficient information.
Whether you're using AI to summarize a lengthy report,
generate ideas for marketing a product,
or outlining a project plan, be sure
to carefully check the quality of the output.
Finally, it's important not
to make assumptions about an LLM's capabilities.
For example, just because it produced high quality output
for a persuasive letter to a customer,
don't assume you will get the same quality output if you use
the same prompt again in the future.
Large language models are powerful tools
that require human guidance for effective use.
Being aware of an LLMs limitations can help you achieve
the best possible results. 


## Yufeng: Experiment with prompt engineering

Hi, I'm Yufeng and I'm a Developer Relations Engineer
at Google Cloud.
I am, but a small part of a much larger team
that focuses on creating useful prompts
for evaluation and to some degree,
training of the models.
I grew up in central Pennsylvania,
in Hershey, Chocolate Town.
And enjoyed kind of math and sciences in high school,
and then went to college at Johns Hopkins
and studied biomedical engineering.
When I graduated college, the company that I worked for
had a very extensive training program
and they were specifically looking
to hire non-computer science majors.
And it wasn't like the normal kind of workplace trainings
that we think of today.
It was like a super compressed crash course.
These days, we'd call it a bootcamp or something like that,
but that didn't exist back then.
Prompt engineering is not something
that necessarily will happen through intuitive use.
Doing prompting properly is really going to help
unlock the capabilities of these conversational
AI systems for you.
Anybody can type in a simple prompt
and get a simple answer back.
But that's not where things are really interesting, right?
It's when you can talk to a system
and get a very tailored and customized answer
based exactly on your use case
that things get really quite exciting.
My advice for folks who are experimenting
with these AI tools for the first time
would be to not get discouraged
if it doesn't produce the results you want initially.
These tools aren't magic
and they can't read your minds.
All they can do is take exactly what you tell them
and then try to do the best they can.
There's kind of what I think of as side context
or implied context that you need to practice
getting it out of your head.
You want it to be long, you want it to be short.
You want it to use simple words, fancy words,
like these sorts of things that you know,
but you might not know you need to write them down.
I would encourage you to just try stuff.
You can go wild with the experimentation.
Try stuff.
You can write a ton of information in
or just like write a little bit,
then write a little bit, then write a little bit,
and just see how it behaves differently.
It becomes just this experimental system
and this process is fun.
As you experiment with this and try new things out,
you'll find that your fluidity and fluency
with these conversational AI tools
will be through the roof
and you'll want to keep trying different prompts.
And who knows?
Maybe it'll have a huge impact on your life.
Only time will tell. 



# KEY PRINCIPLES OF EFFECTIVE PROMPT WRITING

## Write clear and specific prompts

How can you write prompts that produce useful output?
It's generally true that the quality of what you start
with greatly affects the quality of what you produce.
Consider cooking for example.
Let's say you're preparing dinner.
If you have fresh, high quality ingredients,
well you're more likely to produce a great meal.
Conversely, if you're missing an ingredient,
or the ingredients aren't high quality,
the resulting meal may not be as good.
In a similar way, the quality of the prompt
that you put into a conversational AI tool can affect
the quality of the tool's output.
This is where prompt engineering comes in.
Prompt engineering involves designing
the best prompt you can to get the output you want
from an LLM.
This includes writing clear, specific prompts
that provide relevant context.
To gain a better understanding of the context LLMs need,
let's compare how a person and an LLM might respond
to the same question.
Suppose a vegetarian asks their friend,
what restaurant should I go to in San Francisco?
The friend would likely suggest restaurants
with good vegetarian options.
However, if prompted with the same question,
an LLM might recommend restaurants that are not suitable
for a vegetarian.
A person would instinctively consider the fact
that their friend is a vegetarian
when answering the question,
but an LLM does not have this prior knowledge.
So to get the needed information from an LLM,
the prompt must be more specific.
In this case, the prompt needs to mention
that the restaurant should have good vegetarian options.
Let's explore an example that demonstrates
how you can use prompt engineering to improve the quality
of an LLMs output.
Let's take on the task of planning a company event.
You need to find a theme for an upcoming conference.
Let's write a prompt to Gemini to generate a list
of five potential themes for an event.
You can use similar prompts in ChatGPT,
Microsoft Copilot, or any other conversational AI tool.
Now let's review the response.
Well, this isn't what we wanted. We've gotten a list
that seems more related to party themes
than themes for a professional conference.
Our prompt didn't provide enough context
to produce the output we needed.
It wasn't clear or specific enough.
Let's try this again.
This time we'll type the prompt,
generate a list of five potential themes
for a professional conference on customer experience
in the hospitality industry.
This prompt is much more specific, making it clear
that it's a professional conference on customer experience
in the hospitality industry.
Let's examine the response.
This is much better!
We engineered our prompt to include specific,
relevant context, so Gemini is able
to generate useful output.
When you provide clear, specific instructions
that include necessary context, you enable LLMs
to generate useful output.
Keep in mind that due to LLM limitations,
there might be some instances
in which you can't get quality output
regardless of the quality of your prompt.
For example, if you are prompting the LLM
to find information about a current event,
but the LLM doesn't have access to that information,
it won't be able to provide the output you need.
And like in other areas of design, prompt engineering
is often an iterative process.
Sometimes even when you do provide clear
and specific instructions,
you may not get the output you want on your first try.
When our first prompt didn't produce the response we wanted,
we revised the prompt to improve the output.
The second iteration provided instructions that were clear
and specific enough to produce a more useful output. 


## Leverage an LLM's capabilities at work

There are multiple ways to leverage an LLM's capabilities
that work to boost productivity and creativity.
A common one is content creation.
You can use an LLM to create emails, plans, ideas, and more.
As an example, you could ask an LLM to help you write
an article about a work-related topic.
Let's prompt Gemini to create an outline
for an article on data visualization best practices.
The article is for entry-level business analysts.
Notice that the prompt begins with the verb create.
It's often helpful to include a verb in your prompt
to guide the LLM to produce useful output
for your intended task.
The output provides a helpful outline
for a first draft of the article.
You can also use an LLM for summarization.
An LLM can summarize a lengthy document's main points.
For example, you might ask Gemini to summarize
a detailed paragraph about project management strategies.
We'll begin the prompt with the verb summarize
and specify that we want the output to be a single sentence.
Then we'll include the paragraph
we want Gemini to summarize.
The output provides a convenient one-sentence summary
of the paragraph.
While this example shows how you can summarize
a single paragraph, you can ask an LLM
to summarize longer text and documents too.
Classification is another possible use.
For instance, you might prompt the LLM
to classify the sentiment or feeling in a group
of customer reviews as positive, negative, or neutral.
Let's prompt Gemini to classify customer reviews
about a retail website's new design as positive,
negative, or neutral.
The prompt includes the verb classify to guide the output.
The prompt also contains the reviews.
In this example, there are four reviews.
The output accurately classifies the first two reviews
as negative, the third as positive,
and the fourth as neutral.
Consider how you could leverage an LLM
to efficiently complete large classification tasks.
Or you can use an LLM for extraction,
which involves pulling data from text and transforming it
into a structured format that's easier to understand.
Suppose you have a report that provides information
about a global organization.
You can prompt Gemini to extract all mentions of cities
and revenue in the report and place them in a table.
Then we'll include the report in our prompt.
Please be aware that you should not input
confidential information into LLMs.
But in this example, the report is not confidential.
The output displays a table with columns
for city and revenue.
This presents the information in a well-organized format
that's easy to review.
Another use is translation.
You can leverage an LLM to translate text
between different languages.
For example, you might ask Gemini to translate the title
of a training session from English to Spanish.
The output includes a variety of Spanish translations
to choose from and explains the reasoning
behind each translation.
This information can help you choose
the most useful option for your audience.
Or you can use an LLM for editing, such as to change
the tone of a section of text from formal to casual
and to check if the text is grammatically correct.
For example, Gemini can help you edit a technical analysis
about electric vehicles by making the language
more accessible for a non-technical audience.
We'll start the prompt with the verb edit
and specify that the language should be easy
for a non-technical audience to understand.
After this, we'll include the technical analysis.
The output provides a version of the analysis
that an audience less familiar
with the technical details can understand.
This is just one example of how an LLM
can help you edit documents.
LLMs can quickly customize the tone, length,
and format of documents to fit your needs.
One more use for an LLM we'll discuss is problem-solving.
You can utilize an LLM to generate solutions
for a variety of workplace challenges.
When planning a company event, for example,
you could prompt the LLM to find menu solutions
that accommodate the food restrictions of multiple guests
while following a holiday-themed menu.
And here's another example.
Let's say you're an entrepreneur
who recently launched a new copy editing service.
Let's ask Gemini to solve a problem
related to the copy editing service.
We'll ask for suggestions for increasing the client base.
The output provides specific suggestions
for reaching new clients, optimizing services,
and growing the business.
I love these ideas.
Let's ask Gemini to draft an email
so we can easily share these ideas with others.
LLMs can help you brainstorm solutions
for many different types of problems.
I'm definitely excited by the variety of ways
we can leverage LLMs when completing workplace tasks.
It's a very important skill to practice
if you wanna use AI effectively in the workplace.
Coming up, we'll focus more on evaluating output
and iterating on your prompt. 


## Prompts for different purposes

Recall that a large language model, or LLM, is an AI model that is trained on large amounts of text to identify patterns between words, concepts, and phrases so that it can generate responses to prompts. As you’ve been learning, good prompt engineering can help guide an LLM to generate useful output for workplace tasks. In this reading, you’ll further explore how to write clear and specific prompts for a variety of workplace use cases.

- Use cases

As you explored previously, you might use an LLM at work to help boost your productivity and creativity and complete any of these useful tasks: 

    Content creation
    Summarization 
    Classification
    Extraction
    Translation 
    Editing 
    Problem-solving

_Note: The following examples illustrate best practices; they aren’t exact templates to copy for every situation. Your results will vary based on a number of factors, including the specific LLM you’re using. Remember to critically evaluate all LLM output and to iterate on your initial prompt to get the most useful output._

In general, here’s how to make your prompts more effective: 

1. Consider what you want the LLM to produce. The LLM will generate more useful output when you include a specific instruction in your prompt, like create, summarize, classify, extract, translate, edit, or solve.

2. Provide necessary context. The LLM will generate more useful output when you include detailed instructions, with specific guidance about the style or format of the output you want. 

Up next, you’ll examine each of the use cases described earlier by considering an additional example for each.

- Content creation 

No matter your industry, an LLM can help you create content for a variety of purposes, such as blog posts, reports, product descriptions, and taglines. For example, suppose you’re working on an ad campaign for a new line of home appliances. You can ask an LLM to help you create an engaging tagline for one of the products: 

_Act like you are a creative advertising professional who can apply innovative thinking to develop original taglines that project the positive qualities of a product. Create a concise tagline for a washing machine that gets clothes extra clean, has 25 settings, and fits in a small space._

The prompt begins by describing the LLM’s role as a creative advertising executive. Next, the prompt clearly states that the task is to create a concise tagline for a washing machine. Finally, the prompt specifies the product features to include in the tagline.

Pro tip: Assign the LLM a role, job, or function to reinforce the purpose of the prompt and help guide the LLM to produce useful output.

- Summarization 

An LLM can help you summarize many types of texts: reports, customer surveys, meeting notes, emails, and more. For example, the following prompt asks an LLM to provide a summary of a lengthy email: 

_The following text is an email from a software vendor. Summarize its main points in a bulleted list:_

_"I hope this finds you well. It was a pleasure to chat with you at the conference last week._

_Following up with more detail on our pricing plans. Our bronze level subscription gets you access to three of our most popular software products as well as training videos for these products. If you have additional software needs, you can subscribe at the silver level. This level allows you to choose two additional software products, with training videos on those products, as well as gets you 24-hour support on any difficulties you encounter while using the products. Finally, our gold level membership gets you access to all ten of our software products. You get training for all ten products as well as 24-hour support, and you are also the first to enjoy any beta additions to our products._

_Please contact me for the pricing of the level that interests you. We offer monthly subscriptions and a reduced rate for a yearly subscription."_

The prompt begins with useful context about the relevant email. Next, it clearly states that the task is to summarize the main points of the email. Finally, it specifies that the output should be formatted as a bulleted list. 

Note: Be aware that LLMs can sometimes hallucinate, or produce AI outputs that aren’t true. In this case, the LLM might add details to the summary that aren’t included in the source email. Always evaluate LLM output for accuracy before using it.

- Classification 

Text classification is another common workplace application for LLMs. An LLM can help you sort customer service emails into categories based on the content of the email, categorize content in social media posts, and analyze the sentiment or feeling of customer feedback. The following prompt asks an LLM to analyze the sentiment in a customer review: 

_Read these customer reviews and tell me whether the sentiment of the reviews is positive, negative, or neutral._

_Customer Review: I don't know where to begin. We had reservations for 7:00 but they seated us at 7:45. Then, no one came to our table for at least 30 minutes. Our appetizer and main course were mediocre. I did love the dessert, but that wasn't enough to change our experience._

_Customer Review: I love this restaurant. The food is delicious and the service is excellent._

The prompt begins by clearly stating that the task is to analyze the sentiment of a customer review and then specifies the options: positive, negative, or neutral. Then, the prompt includes the relevant reviews under the label “Customer Review.”

- Extraction 

You can also use an LLM to pull data from text and transform it into a structured format that’s easier to understand, known as extraction. For example, this prompt asks an LLM to review a blog post and extract information about products mentioned in the post. 

_Read the blog post below and extract all of the references to items of clothing I can buy and how much each item costs. Create a bulleted list of just these items._

_Blog post: Hey everybody, I want to share what I’m wearing on campus this fall. If I’m going out for the evening, I prefer the raw selvedge denim jeans ($150) paired with the cashmere crew neck sweater ($250). For a more casual look, I like the fleece hoodie ($99) and fleece sweatpants ($129). I also love every color of the striped socks ($15). They pair well with both the jeans and the sweats._

The prompt begins by clearly stating that the task is to extract all the items of clothing mentioned in the blog with their corresponding prices. Next, the prompt specifies that the format of the output should be a bulleted list of the items. Finally, the prompt includes the relevant blog. 

- Translation 

You can leverage an LLM to translate text between different languages very quickly. For example, the following prompt asks an LLM to help translate product descriptions from English to Spanish: 

_Translate our product descriptions from English to Spanish. Maintain the same structure and casual tone that is used in the English version in the Spanish translation._

_Bicycle: Whether you’re exploring city streets or forest paths, our sleek and durable bicycle has it all._

_Rollerblades: Roll into summer in style with our smooth and stylish rollerblades._

The prompt begins by clearly stating that the task is to translate product descriptions from English to Spanish. It also specifies that the Spanish translations should maintain a similar structure and tone as the English originals. Finally, each example contains a label that introduces the product description: “Bicycle" and “Rollerblades.” This format indicates that the LLM should present the output in a similar form. 

Note: As a best practice, confirm that an LLM’s translations are accurate by cross-checking with another translation tool. 

- Editing 

You can also use an LLM to edit and rewrite text. The LLM can help change the tone of the text from formal to casual, or complete a grammar check. For example, the following prompt asks an LLM to help edit a technical report so that it’s less jargony and easier for stakeholders to understand: 

_Edit the language of the following paragraph so that it's easy for a general audience to understand it. Use simpler vocabulary and grammatical structures but maintain the same ideas._

_Site selection for expansion is a complex and multifaceted process. The west side site offers several advantages, including zoning for industrial use and direct access to both a major highway and railroad. However, the site is also located in a jurisdiction with a complex and time-consuming permitting process, and its distance from residential zones may necessitate higher wages to attract workers._

The prompt begins by clearly stating that the task is to edit the text to make it easier for a general audience to understand. Then the prompt specifies that the text’s vocabulary and grammar should be simplified while its main content should remain the same. Finally, it includes the relevant paragraph. 

- Problem-solving

One more use case is problem-solving. You can use an LLM to generate solutions for a variety of workplace challenges, from analyzing sales data to planning an event. For example, the following prompt asks an LLM to help organize a program for a nonprofit organization: 

_We are running a community program to teach children gardening skills. The program runs from June 1 to August 15. We want the children to be able to grow plants that will be ready for harvest by the time the program ends. First, identify a list of 10 plants that can be planted and grown in that time period. Include sources that support the time to harvest for each plant._

_We want the children to grow three plants. These plants should be as different from each other as possible. So next, choose three plants from the list that will provide the children with this variety._

The prompt begins with useful context about the program, such as its main purpose and timeline. Next, the prompt breaks the problem down into two main steps: First, identify a list of 10 plants that fit the timeline, and second, choose three plants from the list that are unlike each other. The prompt also asks the LLM to include sources for the list of 10 plants. Asking the LLM to cite its sources in the output helps you verify the accuracy of the information used to solve the problem. 

Pro tip: Break a problem down into steps to help the LLM process the request and improve the overall accuracy of the output.


## Improve AI output through iteration

Have you ever created a presentation for a client
or designed a website for your new business?
If so, you may have used an iterative process
to achieve your goal.
In an iterative process,
you create a first version, evaluate it,
and improve upon it for the next version.
Then you repeat these steps
until you get the desired outcome.
For example, if you're developing a proposal, report
or other document to share with your coworkers,
you might produce multiple drafts
and make improvements on each draft,
until you are satisfied with the result.
Taking an iterative approach is often the most effective way
to solve a problem or develop a product.
An iterative process is also effective
in prompt engineering.
Prompt engineering often requires multiple attempts
before you get the optimal output.
Most of the time, you won't get the best
result on your first try.
If you try something and it doesn't work,
don't get discouraged.
Instead, carefully evaluate the output
to determine why you didn't get the response you wanted.
Then, revise your prompt to try for a better result.
Let's consider possible reasons you might not get useful
output after creating a clear and specific prompt.
First, differences in large language models
can affect output.
Each LLM is developed with unique training data
and programming techniques
and has different background knowledge
about specific domains.
For this reason, different models might respond
to similar prompts in different ways.
And might fail
to provide an adequate response to some prompts.
Taking an iterative approach
with the LLM you are using will produce the best results.
Second, LLM limitations.
Previously, you learned that LLM output
may sometimes be inaccurate, biased,
insufficient, irrelevant, or inconsistent.
You should critically evaluate all LLM output
by asking yourself the following questions.
Is the output accurate? Is the output unbiased?
Does the output include sufficient information?
Is the output relevant to my project or task?
And finally, is the output consistent if I use the same
prompt multiple times?
If you identify any issues when you evaluate output,
iterating on your initial prompt can often help you resolve
these issues and get better output.
To begin, if you notice there's any context missing
in your prompt, add it.
Your choice of words can also significantly
impact an LLM's output.
Using different words
or phrasing in your prompts often yields different
responses from the model.
Experimenting with different phrasings can help you obtain
the most useful output.
Now that you know more about iterative prompting,
let's consider an example.
Suppose you work as a human resources coordinator
for a video production company.
The company wants to develop an internship program
for students who are exploring careers in animation
and motion graphics design.
The company is based in the United States,
in the state of Pennsylvania, my home state.
Your team wants to partner
with local colleges to provide internship opportunities
for students in Pennsylvania.
As a first step, you need to create a list
of colleges in Pennsylvania that have animation programs.
The list should include necessary details about the colleges
and be in a well organized format
that your team can quickly review.
Let's review an example using Gemini.
Help me find colleges
with animation programs in Pennsylvania.
Next, we'll examine our output.
The output lists colleges in Pennsylvania
that have animation programs,
along with further information related to these programs.
This is helpful information,
but it isn't structured in a way
that your team can quickly reference
when contacting the colleges.
Organizing the information in a table would make it easier
to read and understand,
especially for stakeholders like your manager
who may have limited time.
We can iterate on the prompt by adding context
to specify the desired format of the output.
We'll type show these options as a table.
The output displays a table
that provides useful information about the location
of each college and the specific type of degree it offers.
Now, the list is in a well organized format that's easier
for your team to follow.
Although the table contains most
of the information your team needs,
it doesn't include a key detail,
whether the school is a public or private institution.
Your company wants
to offer internships to students from both public
and private colleges.
We'll add a new request for Gemini
to include the relevant information in the table.
Can you add a column showing whether
they're public or private?
Now, the table includes a column
that indicates whether a college is private or public.
To share this information with your team in a format
that's easy to review and understand,
you can use the Export to Sheets feature.
This will allow your team to easily access
and analyze the data
and make informed decisions based on the results.
You should apply the same iterative approach
to further tasks.
When you develop prompts for additional tasks,
be aware that previous prompts made in the same conversation
can influence the output of your most recent prompt.
If you notice this is happening, you may want
to start a new conversation.
Iteration is a key part of prompt engineering.
By taking an iterative approach to prompting,
you can leverage an LLM to provide the most useful output
for your needs. 


## Activity: Evaluate output and revise prompts

### Activity Exemplar: Evaluate output and revise prompts

Your Prompt log template should include the following components:

1. Each Evaluation of initial output section contains 3–5 sentences about issues identified when evaluating output from the initial prompt and how these issues are related to the prompt. For instance, this section might describe how the output was not sufficient or relevant to the task.

2. Each Revised prompt section contains the final version of the prompt used for that task. These prompts are clear and specific, and they provide sufficient context. Note: Revised prompts are similar but not exactly the same as initial prompts. Sometimes, minor changes are all you need in order to create the output you want.

3. Each Description of revised prompt section contains 3–5 sentences that describe how the prompt was revised to get the desired output. For instance, this section might include details on added context or changed phrasing.



# TECHNIQUES FOR PROMPTING AN LLM

## Discover few-shot prompting

Have you ever created something new
by building upon previous examples?
Perhaps you used a well-received report
as a reference when writing a similar report,
or maybe you used a relevant and engaging website
as a model when designing your own website.
Examples are also useful for LLMs.
Including examples in your prompt can help an LLM
better respond to your request,
and can be an especially effective strategy
to get your desired output.
We're going to explore how to use examples in prompting,
but first, let's briefly discuss the technical term "shot."
In prompt engineering, the word "shot"
is often used as a synonym for the word "example."
There are different names for prompting techniques
based on the number of examples given to the LLM.
Zero-shot prompting is a technique
that provides no examples in a prompt,
while one-shot prompting provides one example,
and few-shot prompting is a technique
that provides two or more examples in a prompt.
Because examples aren't included in zero-shot prompts,
the model is expected to perform the task
based only on its training data,
and the task description included in the prompt.
Zero-shot prompting is most likely to be effective
when you're seeking simple and direct responses.
Zero-shot prompting may not be effective
for tasks that require the LLM
to respond in a more specific, nuanced way.
Few shot prompting can improve in LLMs performance
by providing additional context and examples in your prompt.
These additional examples can help clarify
the desired format, phrasing, or general pattern.
Few-shot prompting can be useful for a range of tasks.
For example, you might use few-shot prompting
to generate content in a particular style.
Let's say you work for an online retailer.
You need to write a product description
for a new skateboard.
You already have descriptions for existing products,
such as a bicycle and roller blades.
You want the skateboard description
to follow a similar style and format.
We'll start with a prompt
that begins with some general instructions.
"Write a one-sentence description of a product.
It should contain two adjectives that describe the product."
We also specify that we want Gemini
to review the examples we provide,
and write the description
of the skateboard in the same style.
Because this is a few-shot prompt,
we need to provide examples that model the style we want.
Each example contains a label,
indicating the product being described,
a bicycle and roller blades.
And each description is one sentence long
and contains two adjectives,
"sleek" and "durable" for the bicycle,
and "smooth" and "stylish" for the roller blades.
Next, we type the label "skateboard."
When we add this label
and leave the product description blank,
we indicate to Gemini that we want it to complete
the description of the skateboard like it did
with the other two product descriptions.
Let's review our output.
The output offers a product description of the skateboard
that meets the criteria we requested,
and is in the same writing style and format
as the examples we included in our prompt.
In this case, two examples were enough
to obtain useful results,
but there is no definitive rule
for the optimal number of examples to include in a prompt.
Some LLMs can accurately reproduce patterns
using only a few examples, while other LLMs need more.
At the same time, if you include too many examples
an LLM's responses may become less flexible and creative
and they may reproduce the examples too closely.
Experiment with the number of examples to include
to get the best results for your specific task.
Now you know a prompting technique
that will help you get better quality output.
Few-shot prompting is an effective strategy
that can help you guide an LLM
to generate more useful responses. 


## Explore chain-of-thought prompting

As you’ve learned, there are prompting techniques that can guide a large language model (LLM) on how to complete tasks. Few-shot prompting is a technique that provides two or more examples in a prompt. And one-shot prompting is a technique that provides a single example in a prompt. 

In this reading, you'll learn a third technique you can use: chain-of-thought prompting. First, you’ll first learn about the main workplace applications for chain-of-thought prompting, and how it can improve the overall quality of LLM output. Then, you’ll review a detailed example of how to write a prompt using this technique.

- Overview 

Chain-of-thought prompting is a technique that involves requesting a large language model to explain its reasoning processes. Chain-of-thought prompting is useful for solving problems that involve step-by-step reasoning. This technique improves the quality of an LLM’s answers in certain cases.

- Benefits 

Chain-of-thought prompting has two main benefits:

1. It can improve the overall accuracy of an LLM’s output. When you divide a task into more manageable steps, you help the LLM produce accurate and consistent results.

2. It can improve the problem solving process. By instructing an LLM to break down the problem, you can better understand the steps used by the LLM to arrive at the solution. 

- Applications 

Chain-of-thought prompting is useful for solving problems that involve mathematical or logical reasoning. For example, you might use chain-of-thought prompting when you make purchasing decisions, analyze sales data, or recommend products based on customer requirements. 

- Prompt design

Chain-of-thought prompts often include one or more examples that demonstrate how to solve a problem in discrete steps. Your prompt should provide context on the problem or task, include an example, and state a request with instructions.

- Example: Create a purchasing code 

Here’s an example of how to design a chain-of-thought prompt for a task at work. Consider an organization with thousands of employees. Each employee is assigned a unique purchasing code that can be used for buying supplies or equipment. First, a technical support specialist creates a unique purchasing code for each employee. To do so, the specialist uses a custom AI solution, approved for use with company and employee information, to help them create the purchasing code with the following chain-of-thought prompt:

_Our organization assigns purchasing codes by combining an employee's department and ID number. All alphabetic characters are lowercase in the purchasing code. Review the examples and then answer the question that follows in the same manner. Explain the steps involved in determining each employee's purchasing code._

_Question: Tiana B works in the Marketing department and has an ID number of 9283. What is Tiana B's purchasing code?_

_Answer: The purchasing code for Tiana B is marketing9283. To determine this, first combine the department (Marketing) with the ID number (9283). This results in Marketing9283. Then, change all alphabetic characters to lowercase. This creates the purchasing code marketing9283._

_Question: Sylvie E works in the Sales department and has an ID number of 2379. What is Sylvie E's purchasing code?_

_Answer:_

This prompt contains three main parts. First, it provides context. Next, it includes an example. Third, it states a request for the LLM to answer. Let’s look more closely at each part.

- Provides context 

The prompt first provides useful context to solve a specific problem:

_Our organization assigns purchasing codes by combining an employee's department and ID number. All alphabetic characters are lowercase in the purchasing code. Review the example and then answer the question that follows in the same manner. Explain the steps involved in determining each employee's purchasing code._

The prompt describes the organization’s method for creating a purchasing code. Because this is a chain-of-thought prompt, the prompt instructs the LLM to follow the example and to explain the steps that determine the purchasing code. 

- Includes an example 

The next part of the prompt includes an example of the steps used to create a purchasing code, presented as a question and answer pair:

_Question: Tiana B works in the Marketing department and has an ID number of 9283. What is Tiana B’s purchasing code?_

_Answer: The purchasing code for Tiana B is marketing9283. To determine this, first combine the department (Marketing) with the ID number (9283). This results in Marketing9283. Then, change all alphabetic characters to lowercase. This creates the purchasing code marketing9283._

Presenting the example in a question and answer format makes it easier for the LLM to follow. 

The question portion of the example includes relevant information about the employee's department and ID number, and asks for Tiana B’s purchasing code based on this information. 

The answer portion of the example demonstrates the step-by-step reasoning that the specialist wants the LLM to use to determine the purchasing code. 

Note: You may not always be able to provide a useful example in your prompt. In that case,  simply state that you want the LLM to explain its reasoning. The quality of your results will depend on your prompt and the specific LLM you’re using. Try including the following language in your prompt to get the best results: 

    "Solve the problem in a step-by-step manner."

    "Explain each step used to determine the answer."

- States a request

Finally, the prompt includes the specific question the LLM should answer:

_Question: Sylvie E works in the Sales department and has an ID number of 2379. What is Sylvie E’s purchasing code?_

_Answer:_

The question follows the pattern of the previous example to make it easier for the LLM to provide a similar answer. The field after the label “Answer:” is blank to indicate that the LLM should complete the answer.


## Rachna: Improve prompts through exploration

Hi, I am Rachna.
I am a software engineer at Google.
I work on a team called Central Knowledge Management,
and we're responsible for making sure that developers
have access to all the information that they need.
One of the most important things
to learn about in AI is prompting,
which is just figuring out what text to input
to get the response you want.
One of the ways to find the most effective prompts for LLMs,
or large language models,
is to just iterate rapidly on them
and try a wide variety of different prompts out.
So maybe if it was not funny enough,
the next time you could try prompting the LLM
to make it more funny.
Or if it's too vague,
you can use a prompt
that specifically asks the AI not to be vague.
And trying out a lot of different things this way
will usually give you good results.
One way you can change how you're using LLMs
to allow them to be more creative or be more specific
is just based on how much context you put in.
So if you want the LLM
to give you a pretty creative response,
you can just try a very short prompt.
If you want it to be very specific,
you can put in a lot of examples,
and then it'll conform more to your examples.
Another technique that's really interesting
is chain-of-thought prompting,
where you ask the model to reason out its own response.
So if you're asking the model to follow some math,
a mathematical equation,
you can ask it to first break it down into steps
and then do the first step
and then the second step and so on.
And getting the LLM to do multiple steps
can sometimes make it much more accurate.
One slightly more unexpected prompting technique that we use
is asking the model to react to its own responses.
So sometimes I'll ask the model for a response,
and then I'll say, is this response vague?
And then if it answers yes,
then sometimes I'll throw that response out.
So I'll let it do some of some of my work for me.
The more you experiment and the more creative you are,
the better.
Keeping up with AI can feel a little bit
like running on a treadmill sometimes,
and it's always getting faster and faster,
and there's so many new things that are changing,
but I think that's also what makes it really fun. 


## Prompt engineering best practices

Large language models (LLMs) react to what we ask them — the better the input, the more useful their output. Use this guide to create effective prompts that help LLMs perform their best, so you can get the most valuable response.

- Specify the task

LLMs are trained on massive amounts of data. You need to get specific about your desired result, so the model can deliver a focused output. Be clear about what you want LLMs to do by providing sufficient parameters. Use straightforward language, and structure queries in a logical way to enhance how the model interprets your request. No specific set up is best; write intuitively and focus on clarity.

Example: _Draft an informal email to my manager requesting time off._

- Provide necessary context

Context shapes how LLMs respond to a prompt by providing important information about your expectations. With relevant context, it is more likely LLMs will generate useful output.

Include key details about your request to give LLMs the information they need to generate useful output. Here are some questions to consider when writing an effective prompt:

1. Who’s the target audience? Specify relevant qualities of the audience, such as their age, profession, or level of understanding on a topic.

2. What tone should the model use? Clarify the voice and style in which LLMs should use to most effectively convey their message. You might want an output that’s casual and friendly if you’re using it to communicate with a peer, or something more professional and persuasive for clients. 

3. How should LLMs structure output? Specify the format LLMs should use to order the information it provides. You may include guidance about length or specify a type of layout, such as a bulleted list or table.

4. What’s the output’s goal? Identify what you want LLMs to accomplish with a given prompt. For example, if your prompt asks the model to explain a concept, the goal might be to ensure beginners in that specific field gain a working understanding of the topic. Giving an LLM a goal will help shape the outputs to your specific needs.

Example: _Write a friendly email to my HR coworker thanking them for their collaboration on a recent project so they know their contributions were invaluable._

 - Provide references

Providing LLMs with reference materials that achieve your goals or resemble what you want to create can help generate more useful outputs. Whether you’re including your own work, broader sources, or both, you also want to explain clearly how these reference materials relate to your prompt for the best possible results.

Example: _Draft a list of potential campaign slogans for a sunglass company in the writing style of 1960s billboard advertisements._

- Evaluate your output

Each model has a unique training set, relies on different programming techniques, and is developed at a specific point in time. As a result, some LLMs may know more about certain topics than others or may experience a knowledge cutoff. Models can occasionally hallucinate, too. 

Before you use an AI-generated output, critically assess the output to ensure it's acceptable and beneficial to you. This may involve conducting some research after LLMs produce their output. When evaluating an output, ask yourself: 

1. Is this response accurate? Confirm the information is up-to-date and factual. 

2. Is this response unbiased? Evaluate whether the response is fair and impartial, accurately represents populations, and avoids preferential treatment for certain individuals or groups.

3. Does this response include sufficient information? Ensure the response delivers a comprehensive and satisfactory response to your query. 

4. Is this response relevant to what I need? Check that the output relates to your prompt and aligns with the context, topic, and task you outlined. 

5. Is this response consistent? Verify that your response isn’t an outlier. If you aren’t sure, try prompting LLMs multiple times in different ways to ensure the outputs give you similar information. 

If you determine an output is unacceptable, try to add more context to the initial prompt to generate a more focused response: 

Example: The output from a prompt like _What’s a conditional?_ might be broad, varied, or irrelevant to your needs, since that term has different meanings in various contexts.

Iteration: Instead, a prompt like _Explain ‘conditionals’ to a beginner coder like a textbook_ would most likely produce a more targeted, useful output by specifying the audience, tone, and discipline.

- Take an iterative approach

Whatever the reason, a LLM might not produce what you need the first time you ask for it. You can still arrive at your desired outcome with some iteration, by refining the initial prompt, issuing follow-up requests, or giving LLMs feedback.

To successfully revise a prompt, keep what worked and adjust the input from there. You might change some phrasing (like whether the prompt is a command or question), reorder the prompt’s components (like whether you start or end with an example), or provide additional context to help narrow LLMs’ responses.

Example: _Summarize the following meeting notes._

Iteration: _Summarize the following meeting notes and identify key takeaways._

Further iteration: _Summarize the following meeting notes, identify key takeaways, and list the most urgent action items with their deadlines._

To efficiently issue follow-up requests, ask the model to make adjustments without repeating the initial prompt, like a back-and-forth dialogue. LLMs are able to build off of prior interactions within a conversation, which means you can focus on making targeted, individual adjustments until you have everything you need.

Example: _Summarize the following meeting notes._

Follow-up: _What were key takeaways from this meeting?_

Second follow-up: _What are the most urgent action items and their deadlines?_



## Activity: Use AI to inform work-related decisions

### Activity Exemplar: Use AI to inform work-related decisions

Your Prompt log for event planning tasks template should include the following components:

1. Each Prompt section contains the final version of the prompt used for that task. These prompts are clear and specific and provide sufficient context. 

2. Each Prompt description and output evaluation section contains 3–5 sentences that describe how you engineered the prompt to get the desired output, any prompting best practices or techniques you incorporated, and what factors you considered when you evaluated the output.



# WRAP-UP MODULE 3

You've learned a lot about writing prompts
that you can apply to workplace tasks.
In this section, we discussed large language model,
or LLM output.
We examined how LLMs produce their output
and potential issues you might encounter in the output.
After this, we focused on a key principle
of prompt engineering, creating clear and specific prompts.
You learn just how important it is to specify
what you want the LLM to do,
and to include supporting context
to help it provide better output.
We then went on to discover how to improve the quality
of AI output through iteration.
It's essential that you evaluate your output,
and then revise your prompt as needed.
Lastly, we learned about few-shot prompting,
which involves providing examples to guide the LLM.
I wanna offer a final tip before I go.
We focused on prompting large language models.
You can use the same general principles
when you prompt other kinds of AI models too.
For instance, the next time you want to use AI
to generate an image,
try to be as clear and specific as possible,
and then iterate to get closer to the output you want.
It's been great guiding you through the process
of prompt engineering, I hope you continue to apply
and develop these skills
as you leverage conversational AI tools in the workplace.
To continue learning, I encourage you to explore the topic
of using AI responsibly as part of Google AI Essentials. 
