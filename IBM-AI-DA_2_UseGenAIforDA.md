# | Generative AI: Enhance your Data Analytics Career |

# → USE OF GENERATIVE AI FOR DATA ANALYTICS

In this module, you will have the skills and knowledge to effectively use Generative AI to derive insights, create visually compelling data representations, and construct interactive dashboards for data analytics pipelines. You will also understand the importance of ethical practices in utilizing generative models for data analytics.

Learning Objectives:

    Use generative AI tools to create Python code to perform various operations relevant in drawing insights from a given data.
    Use hal9’s free plan to generate statistical data analysis and find missing data.
    Apply Generative AI to extract valuable insights from diverse datasets.
    Use Generative AI tools and platforms to create informative data visualizations.
    Acquire practical skills in building interactive dashboards by using Generative AI tools.
    List some of the generative AI-driven frameworks used for storytelling.
    Explore Generative AI for generating real-time insights.
    Evaluate real-world case studies showcasing the successful application of Generative AI in deriving meaningful insights and producing impactful visualizations.
    Analyze the ethical considerations associated with using Generative AI in data analytics.
    Explore responsible practices and considerations for ensuring transparency and fairness.


# GenAI FOR DATA VISUALIZATION & STORYTELLING

## Generative AI for Data Insights 

Welcome to this video on
how generative AI is used for drawing data insights.
In this video, you will see a demo on how you can use
generative AI tools to perform
various operations relevant in
drawing insights from a given data.
After watching this video,
you'll be able to use
generative AI to create Python code that
will perform various operations
relevant in drawing insights from a given data.
Use hal9's free plan to generate
statistical data analysis and find missing data.
Assume that your cleaned data is available in a CSV file.
You could then use a generative AI model like
GPT-3.5 to create a Python code
to generate the analysis you require.
For example, a symbol prompt for
the tool would be create a Python code
to generate the statistical description of
cleaned data available in a CSV file.
The response of the model would look something as shown.
This valid Python code uses the pandas library to
generate statistical descriptions of
data using the described function.
The same prompt can also be enhanced to include
advanced aspects for creating data insights. For example,
you could add features like univariate, bivariate,
and multivariate analysis of the data to the prompt,
create a Python code to perform univariate, bivariate,
and multivariate analysis of
data available in a CSV file.
The response would show the code,
this code would now generate
a detailed statistical description of the data.
It will run the univariate analysis
for any selected attribute
and bivariate analysis for any pairs of attributes.
For the multivariate analysis,
it will plot a pair plot,
which is an ensemble plot consisting of
bivariate analysis of all pairs of data attributes.
Further, you could ask the model to
add certain aspects to this code.
For example, you want to select
the five best features with
the best relationship with the target attribute.
You may also ask the system to create
a script to engineer
new features that fit the data better.
Both of these tasks can be achieved
using the following prompt in a continued chat.
In the code above, add the aspects of
selecting the five best features
that fit the target attribute
as well as the aspect of
engineering new features for the same.
In response, the model will generate
a detailed code as shown below.
It uses the select best method under
the scikit-learn library to
calculate the best features for the data.
Further, it also creates new polynomial features using
the polynomial features method
and the scikit-learn library.
Let's move to another tool to demonstrate
how generative AI can quickly and
effectively generate insights from the data.
We're using hal9's free plan
for this part of the demonstration,
we're using a student's performance dataset
titled student-mat.csv.
The data was collected from
school reports and questionnaires.
The data attributes our student grades and demographics,
social and school related features.
Once we upload the dataset and click create,
the platform will suggest
prompts which can be used to find insights.
Let's try to find the distribution
of student ages across schools.
The response is a graphical
representation of the distribution.
We can see that school GP has 57 students at age 18,
while MS has 25.
You can save the generated responses if you wish.
Now let's look for missing values in the dataset if any.
The response shows some rows from the dataset
a tabular summary of
column names and account of missing values.
The response shows that no values are missing.
Let's get the statistical insights on the whole dataset.
The basic statistical analysis summary
contains count, mean,
STD, min,
quartile percentages for
quantitive columns and Max values.
For categorical columns it
shows the unique values with their count.
For instance, unique values in school are GP and MS.
In this video, you learned that you
can use generative AI tools to create
Python code to perform
various operations to draw insights from given data.
You can add features like univariate,
Bivariate, and multivariate analysis of the data.
You can use hal9's free plan to generate
a statistical representation of
the data and find missing values. 


## Generative AI for Data Visualization

Welcome to generative AI for data visualization.
After watching this video, you'll be able to explore data sets and generate charts
and get exploratory insights into the relationship between variables.
When it comes to developing or creating visualizations from data,
there are many tools available besides those provided by the big names like IBM,
Google, Microsoft, and Salesforce.
In this video, we will explore some of the generative AI tools that are either
available free or on a trial basis.
Data professionals can use these tools to create visualizations quickly and
easily without spending hours writing codes.
In this demonstration, we will explore columns.AI.
An AI-assisted storytelling platform, and see how it can easily generate charts.
Let's begin by initiating a story.
First, let's upload our student-mat.CSV dataset.
Then we submit and we will see a small preview
of the data with some options to configure and we'll save it.
We can explore the data set once it's uploaded.
We can see some autogenerated charts and statistics from the data, such as the age
attribute showing the minimum age of 15 and a maximum student age of 22.
Let's find the total number of male and female students in the data set.
We can see the bar chart for
the requested prompt displays the distribution of the 395 male and
female students, and if we hover over each bar in the chart, we can see that there
are slightly more female students with 208 compared to the 187 male students.
We then click Apply to use this chart for our data set.
We can also use the wizard to create a chart.
Now we will create a pie chart to represent the average weekly alcohol consumption,
which is identified by the Walc value for each gender.
If we click summary and then select Smart Title, a title is generated for the chart.
Now let's generate some insight on this chart.
And here it is.
We can edit the annotated insight if we want to.
We can also change the appearance of the chart easily.
Once we're done with the customizations,
we can download it either as a PNG or SVG image file or as a CSV or JSON data file.
For our next demonstration, we will use Akkio's free trial version.
We will use the retail sales data.CSV dataset,
which is one of the sample data sets provided by Akkio.
To begin, we create a new project and pull the data set into the project.
Now we will use Chat Explorer to get an exploratory insight on the relationship
between marketing spend and sales by generating a scatter plot.
We can get the details on the approach used to generate this chart.
And we can download it as well.
Let's generate a bar chart which shows the average sales by area.
Well, that was easy.
Now, let's generate a correlation matrix on the data attributes as a heat map to
understand the correlation amongst them.
The color of each square indicates the strength and direction of the correlation.
To interpret the chart, we look at the colors of the squares.
Darker colors represent stronger correlations,
while lighter colors represent weaker correlations.
Positive correlations are shown in one color,
while negative correlations are shown in another.
Thus, we can identify which attributes are strongly correlated and which are not.
To verify any outliers, let's generate box plots.
With a single prompt the tool has generated the box plots for
all possible attributes from the data set.
We can also get histograms for
all attributes to understand the spread of values.
In this video,
you learned that you can use free generative AI tools to generate charts.
You can use free generative AI tools to analyze data and
generate insights into data.
You can use free generative AI tools to get exploratory insight into
the relationship between variables.
And you can use free generative AI tools to create correlation matrices,
boxplots, and histograms from data. 


## Generative AI for Creating Dashboards

Welcome to Generative AI for Creating Dashboards.
After watching this video,
you'll be able to define the purpose of creating dashboards.
Describe some of the generative AI driven frameworks that develop interactive
dashboards.
Discuss the features of these frameworks.
Dashboards present data in an understandable visual format.
These are practical tools that help individuals and
businesses make well-informed decisions.
You need a certain level of experience with data visualization and
design to create impressive dashboards.
Generative AI streamlines creating dashboards by automating intricate design
choices.
It helps data professionals create dashboards without much training.
Generative AI makes creating interactive dashboards easier and
improves user experience.
Some of the generative AI driven frameworks that develop
dashboards quickly and easily are Dash, ChatGPT, Tableau AI, and
Einstein Copilot, Akkio, Thoughtspot, DataSquirrel, and Sisense.
Dash is a Python-based framework for building analytical web applications.
Dash can interact with large language models,
LLMs like ChatGPT, to create dashboards that are interactive and customizable.
Data analysts combine the power of Dash with ChatGPT to create dashboards in a web
application format.
ChatGPT, developed by OpenAI, is a conversational AI language model.
Although it is not specifically designed for dashboard creation,
it can be integrated into applications to provide natural language interaction and
enable users to query and request information conversationally.
You can always write a prompt to fetch the data set to write a code for
creating a dashboard.
Tableau AI is an advanced version of Tableau that helps data
analysts get intelligent, personalized, and
contextually relevant insights within their workflow.
Using the Einstein Trust later as its foundation,
Tableau AI enables data analysts to implement ethical AI-driven
experiences without compromising data privacy and security.
Einstein Copilot is like a helpful assistant in Tableau,
it helps data analysts be more productive by providing advice on how to make better
visualizations and dashboards.
It also speeds up creating dashboards by automating repetitive tasks.
Akkio can create graphs and
charts with GPT-4 through specialized prompt engineering.
Data analysts can interact with data using Akkio's chat explore feature.
Using simple conversations, Akkio with GPT-4 can generate various visual
representations of data, such as scatter plots, line plots, bar charts, and so on.
Once you create the charts, you can compile them into a dashboard.
It's important to note that having a paid subscription is recommended for
optimal dashboard creation in Akkio.
Thoughtspot is an AI-driven analytics platform that allows users to create
interactive dashboards using natural language search.
Its AI capabilities enable automated data analysis, anomaly detection, and
intelligent recommendations for dashboard designs.
With the Thoughtspot product, you can create personalized,
interactive, and actionable insights even from the cloud data.
DataSquirrel, an AI-powered data analytics platform,
is the Go-to business intelligence BI platform.
Even without technical knowledge or skill,
you can easily create attractive visuals by simply uploading the data files.
The platform automatically cleans the inconsistencies and
offers auto-analysis and customizable dashboards.
Its GDPR PDPA compliant features enables secure data processing,
anonymization, and easy collaboration.
Data analysts can use it across industries like B2B ecommerce,
HR, financial accounting, and survey data analysis.
Sisence is a BI platform. It uses AI technology to
provide advanced analytics and dashboard creation capabilities.
Its AI-powered features include automated data preparation,
natural language processing, and machine learning algorithms.
In this video, you learned that generative AI streamlines the process of creating
dashboards by automating intricate design choices.
Some generative AI-driven frameworks to develop dashboards are Dash ChatGPT,
Tableau AI, and Einstein Copilot, Akkio, Thoughtspot, DataSquirrel, and Sisense.
Dash can interact with LLMs to create interactive and customizable dashboards.
ChatGPT is not specifically designed for dashboard creation, but
can write dashboard code.
Using the Einstein Trust Layer,
Tableau AI can create dashboards by automating repetitive tasks.
Akkio can create dashboards through specialized prompt engineering.
ThoughtSpot can create interactive dashboards using natural language search.
DataSquirrel can auto-clean, analyze, visualize, and repeat data.


## Generative AI for Storytelling  

Welcome to Generative AI for Storytelling.
After watching this video,
you'll be able to explain the key aspects of storytelling and data analytics.
List some of the generative AI-driven frameworks used for storytelling.
Discuss the features of these frameworks.
Storytelling and data analytics is the art of transforming raw data into a compelling
narrative to communicate insights, findings, and
the significance of the data to a broader audience.
It goes beyond presenting raw numbers and statistics,
aiming to make data more accessible, understandable, and impactful.
There are several key aspects of storytelling and data analytics.
Data visualization includes graphs, charts, and
other visual representations to make complex data more engaging.
Logical organization means giving your narrative a clear and logical structure.
Contextualization includes providing a context for
the data to explain its relevance to the goals.
Data analysts must also engage their audience by encouraging questions,
discussions, and interactions.
Incorporating anecdotes, case studies, or
real world examples makes your data more relatable.
An audience-centric approach involves tailoring the narrative to resonate with
the audience's interests and priorities.
A compelling narrative also gives a clear call to action such as making a business
decision, changing a process, or
further exploration based on the insights derived from the data.
Some of the generative AI-driven frameworks that organizations use to
create compelling stories include Google Slides with Duet AI,
Generative Reports, DesignerBot, ChatGPT, and Bard.
Let's explore these frameworks.
You can use Google Slides, a cloud-based software to tell impactful stories through
creating, editing, and collaborating on presentations online.
Duet AI is an add on feature for Google Slides by Google,
which gives an AI boost to your slides.
Using Google Slides with Duet AI, you can generate images,
create new slides, and summarize a presentation.
Accio's generative reports allows you to convert data into actionable insights
swiftly.
This innovative AI tool generates reports tailored to your objectives.
Simply link your data, describe your project, and
receive a report designed to enhance marketing expenditure, predict revenue,
assess leads, or address various needs.
The key features include connecting to real-time data sources, sharing reports
with clients, and customizing reports with your business's branding.
DesignerBot from beautiful.ai can create personalized presentations for you.
Based on your description,
Designerbot generates slides using these smart slide templates.
It allows you to customize your presentation using visual aids like
Venn diagrams, XY plots, flowcharts, and infographics.
It also enables you to expand your content, summarize it,
write it in a different tone, or translate it into another language.
You can provide context in your prompt for unique outcomes.
DesignerBot can convert text-based documents, PDFs, or URLs into slides.
Chat GPT by OpenAI and Bard by Google are two conversational generative AI chatbots
you can leverage to prepare your presentation for storytelling tasks.
Both tools allow you to employ prompts to enhance content creation,
refine narrative elements such as titles, headings, bullet points, introductions,
conclusions, and improve the overall structure of your presentation.
In this video, you learned that storytelling in
data analytics is the art of transforming raw data into a compelling narrative.
The critical aspects of storytelling and data analytics include data visualization,
logical organization, contextualization, engaging your audience, anecdotes and
examples, audience-centric approach and call to action.
Some generative AI-driven frameworks organizations use to create
compelling stories include Google Slides with Duet AI, Generative Reports,
DesignerBot, ChatGPT, and Google Bard.
Using Google Slides with Duet AI allows you to generate images,
create slides, and summarize a presentation.
Generative reports allows you to convert data into actionable insights.
DesignerBot from beautiful.ai can create personalized presentations swiftly.
ChatGPT and Bard allow you to enhance content creation,
refine narrative elements, and enhance the overall structure of your presentation. 


## Successful Implementation of Generative AI for Data Visualization and Storytelling 

Welcome to Successful Implementation of Generative AI for DV and Storytelling.
After watching this video, you'll be able to identify the impact of generative AI in
data-driven storytelling and explore the real-world application of generative AI.
Data visualization and storytelling are entering a new phase of creativity and
innovation because of the development of generative artificial intelligence (AI).
Although the field is still developing,
there have been several noteworthy cases where businesses have effectively used
generative AI to turn data into visually engaging stories.
Let's examine three compelling case studies that highlight how generative AI
is changing the field of data-driven storytelling.
Elisa, Finland's leading telecom operator, has seamlessly integrated Copilot for
Microsoft 365, an AI assistant designed to simplify tasks in popular applications.
This adaptable tool has proven useful across various functions,
from financial administration to sales and customer service.
One notable feature emphasized by Elisa's business director Joni Oksanen,
is Copilot's ability to autonomously capture meeting notes.
This not only streamlines team discussions, but
significantly enhances overall productivity.
Copilot eliminates the need for manual data entry and customer service and sales,
providing direct access to customer data from various discussions.
This results in a more comprehensive understanding of customer needs,
ultimately improving the overall customer experience.
Elisa has taken it a step further by integrating Copilot with voice, data and
customer service solutions, emphasizing its commitment to innovation.
The platform's secure environment ensures the safe handling of sensitive data,
making it a reliable choice for managing critical business information.
Lindt Canada and Newcomp Analytics have been working together for
15 years with a focus on streamlining their supply chain.
This collaboration involves using Cognos analytics to gain insights and
improve overall business intelligence.
To stay current, Lindt's supply chain management team decided to transition from
legacy tools to the modern data analytics toolset offered by Cognos analytics.
This involved integrating new data feeds from transportation providers and
warehouses and consolidating them into a master data set.
This migration significantly improved Lindt's supply chain management team's
capabilities in business intelligence.
The consolidated data view has enabled the team to make more informed decisions based
on comprehensive and up-to-date information.
A notable addition to Lindt's implementation is the use of AI-powered narrative BI.
This solution plays a key role in optimizing marketing strategies.
Whether you're a seasoned marketing professional or someone with limited data
expertise, the solution extracts insights and natural language,
facilitating informed decision-making without the need for technical details.
Writingmate.ai, a platform using narrative BI, shows how businesses can leverage this
technology to better understand their data for more informed decision-making.
SparkBeyond's Discovery platform is transforming fraud detection technology
with advanced AI capabilities.
It detects fraud and identifies up to 80% of potential losses by analyzing data,
recognizing subtle patterns, and preventing significant losses.
During the pandemic, the platform excelled in spotting criminal activities amid
the shift to remote work. Discovery sent alerts to at risk individuals by catching
subtle signals hidden in the vast data sets.
Discovery's capabilities extend to recognizing trends like account takeover
and money laundering.
It also flags suspicious calls and customer patterns,
offering a quick response tool to reduce various types of fraud.
Discovery plays a valuable role in reducing false positives and
streamlining claim processing in the insurance sector.
It effectively curbs fraud across the supply chain for pharmaceuticals,
demonstrating its adaptability across different industries.
A major US card issuer and
online bank turned to SparkBeyond to enhance its fraud detection capabilities.
The platform seamlessly integrated with the client's secure cloud,
resulting in consistent identification of compromised cards.
This led to the mitigation of 8% of total fraud losses through daily card reissue,
making an impressive $5 million impact within 6 months.
In this video, you learned that generative AI is revolutionizing data-driven
storytelling, bringing creativity and innovation to data visualization.
Elisa has seamlessly incorporated Copilot for Microsoft 365 into its operations.
It uses Copilot for simplifying tasks across various functions,
from financial administration to customer service.
Lindt's partnership with Newcomp Analytics focuses on optimizing and
streamlining the intricacies of the supply chain.
By transitioning to Cognos Analytics modern toolset,
Lindt improves its business intelligence capabilities.
SparkBeyond's Discovery platform provides fraud detection
by leveraging advanced AI technologies, and it can recognize trends and
reduce false positives in various industries.



# GenAI CONSIDERATIONS in DA

## Considerations While Using Generative AI in Industries

Welcome to Considerations While
Using Generative AI in Industries.
After watching this video,
you'll be able to summarize
the key considerations while using
generative AI in various industries,
list the industry-specific considerations
of using generative AI.
The application of generative AI
is not without due consideration.
When using generative AI in data science,
several considerations are crucial
to ensure the effectiveness,
fairness, and responsible use
of the technology in various applications.
The key considerations to take into account while
using generative AI are data considerations,
model considerations, and ethical considerations.
Generative AI models are trained on large data sets.
The effectiveness of these models
depends on the quality of the training data.
If it is inaccurate and biased,
the output data is likely to amplify those biases.
Therefore, it is crucial that data scientists thoroughly
evaluate the quality and representativeness of the data,
and eliminate bias when training generative AI models.
The choice of generative AI model and training parameters
determines the explainability and
interpretability of the generated output.
Explainability refers to the model's ability to
provide clear insights into decision-making process,
and interpretability refers to
the ease with which we can understand its output.
Data scientists need to select a model that
provides both explainability and interpretability.
To improve interpretability, they need to use techniques
such as feature attribution and partial dependence plots.
The ethical implications of using
generative AI must be carefully considered.
Generative models can be misused for
malicious activities such as creating deep fakes,
manipulating public opinion,
and spreading misinformation.
Data scientists must establish
ethical guidelines for use of generative AI.
They must ensure that their models are used
responsibly and do not
contribute to malicious activities.
Let us now understand the key considerations while using
generative AI and data science for
specific industries such as finance,
healthcare, retail, and media and entertainment.
In the finance industry,
data considerations involve handling of sensitive data,
regulatory requirements,
and possible impact on financial markets.
Therefore, data scientists must
use encryption techniques to comply with
data privacy regulations and
establish clear data access protocols.
Generative AI models in finance
must be robust against adversarial attacks,
in which malicious actors intentionally
manipulate the model's inputs
to produce misleading outputs.
Data scientists must use interpretability techniques
such as feature attribution and partial dependence plots.
They must also ensure robust optimization to
improve the model's resilience
against adversarial attacks.
Generative AI models can
perpetrate existing biases and training data,
leading to discriminatory financial decisions
such as bias loan approvals.
Data scientists need to check
the data for potential biases by
using techniques such as
fairness metrics, and adversarial training.
The healthcare industry generates
highly sensitive data such as medical records,
imaging data, genetic information,
and clinical trial data.
Data scientists should carefully evaluate
the quality and representativeness of the data,
and ensure that it accurately reflects
the patient's population and is free from bias or error.
Generative AI models used in
the healthcare industry must be
compliant with HIPAA and other regulations.
They need to be highly accurate, interpretable,
and robust against adversarial attacks
that could lead to misdiagnosis,
inaccurate treatment recommendations,
or manipulation of patient data.
Data scientists must select models that can
anonymonize patient data and control data access.
Ethical considerations in healthcare
must include transparency and consent.
It is important to inform patients
about the use of generative AI in
their care and explain
the limitations and potential risks of the model.
Data scientists must obtain
informed consent from patients,
and ensure that they have the right to
access and review their AI-generated data.
They should also check the data for potential biases,
and use techniques to mitigate bias.
In the retail industry,
data considerations include customer purchase history,
product specifications, market trends,
and social media interactions.
Data scientists must select generative AI models that
generate accurate product designs
and effective marketing strategies.
They should use data augmentation
techniques to ensure that
the augmented data retains
the underlying patterns and
distribution of the original data.
In the retail industry,
the choice of generative AI model architecture
depends on the task at hand.
Generative adversarial networks, GANs, for example,
are well suited for generating realistic product images,
while recurrent neural networks,
RNNs, are effective in predicting purchase patterns.
Data scientists should use
interpretability techniques to
create accurate model predictions.
Ethical considerations in the retail industry include
the regulation of customer data such
as personal information and purchase history.
Generative AI models can perpetuate biases present in
training data leading to
unfair recommendations for a product.
Data scientists must use techniques to mitigate bias,
ensure compliance with privacy regulations,
implement robust data security measures,
and obtain informed consent from
customers before using their data.
In this video, you learned that
while using generative AI models,
data scientists need to look into data,
model, and ethical considerations.
The output's effectiveness depends
on the training data's quality.
Data scientists need to select a model that
provides both explainability and interpretability.
Generative AI models can be
misused for malicious activities.
Specific industries have specific data,
model, and ethical considerations. 


## Challenges While Using Generative AI

Welcome to Challenges While Using Generative AI.
After watching this video,
you'll be able to summarize the challenges while using generative AI in data science.
Discuss the three key challenges while using generative AI in data science.
Data professionals face various challenges when using generative AI in multiple
industries.
These challenges go beyond the well known concerns of bias, robustness,
privacy, consent, and ethics.
You can broadly categorize these challenges into technical,
organizational, and cultural issues.
The use of generative AI presents several technical challenges,
such as quality and availability of the training data, striking a balance between
model complexity and interpretability, the resource intensive nature of training
large scale computational models, and the lack of standardization and tools.
Addressing these challenges requires the responsible deployment of generative AI
technologies.
Generative AI models are highly data driven.
The quality of training data significantly impacts the performance of these models.
It's often challenging for data professionals to find relevant,
high quality and well-labeled data, especially for
niche applications or when dealing with sensitive data.
Generative AI models can be difficult to interpret,
which makes it challenging to understand the model's decision making process,
assess its reliability, and identify potential biases.
Data professionals may face AI hallucinations while using generative AI
models.
This term refers to the generation of inaccurate or
illogical information by generative AI models due to flawed training,
data inappropriate model architectures, and inadequate evaluation methods.
Training and running generative AI models can be computationally expensive,
requiring specialized hardware and software infrastructure.
This constraint can pose a significant barrier for
organizations with limited resources or those operating in cloud environments.
The generative AI technology is still in the early stages and
requires more standardization regarding model architectures,
training procedures, and evaluation frameworks.
This fact makes it difficult for
data professionals to effectively compare the different models and tools.
Implementing generative AI in organizations comes with its own
set of challenges.
It can raise copyright and intellectual property issues.
The need for specialized skills in AI and
data science requires investment in training or hiring.
Integrating these models into existing systems is challenging, too, as it
requires change management and careful calculation of return on investment, ROI.
Overcoming these organizational challenges requires a strategic approach, including
process adjustments, skill development, and commitment to ethical practices.
Currently, some companies disallow the use of public generative AI models to create
content because it can create copyright and intellectual property issues.
To overcome these issues,
organizations can develop their own customized generative AI models.
With time,
more specific guidelines about the use of generative AI will likely be established.
The demand for machine learning engineers and
data scientists with expertise in generative AI is growing consistently.
However, the supply of skilled professionals is limited,
making it challenging for
organizations to build and maintain in-house generative AI capabilities.
Integrating generative AI into existing data architectures and
workflows can be complex and time consuming.
This integration often requires changes to data pipelines,
decision making processes, and risk management frameworks.
Introducing generative AI into organizations can be met with resistance
from stakeholders concerned about job displacement, data privacy, or
the potential impact on decision making processes.
Effective change management strategies are crucial for successful adoption.
Determining the return of investment or ROI for
projects involving generative AI can be challenging, as some applications of
generative AI may take a longer time to show tangible results or benefits.
Also, it's challenging to measure the outcomes that are real and valuable, but
not easily expressed in monetary terms.
Data professionals must develop robust evaluation frameworks to assess the impact
of generative AI initiatives.
Organizations face cultural challenges, too while implementing generative AI.
They may want to avert risk and have issues related to data sharing and
collaboration.
Establishing trust and transparency and a culture of continuous learning and
adaptation may also be challenging.
Successfully navigating these challenges involves promoting secure data practices,
enhancing transparency, and fostering a continuous learning mindset.
Generative AI is a relatively new technology, and many organizations may be
hesitant to embrace it without clear assurance about its impact.
This aversion can hinder innovation with generative AI applications.
Generative AI models require large amounts of data for training.
However, organizations concerns about the security of their proprietary data makes
them reluctant to share it.
This lack of data sharing can limit collaboration and
hinder the development of more robust and generalizable models.
Generative AI models are powerful but complex and opaque tools.
Because of this opaqueness,
the stakeholders may not find outputs reliable.
Building trust and transparency requires open communication,
explainable AI techniques, and transparent governance frameworks.
Generative AI models must be continuously updated and
adapted to changing data distributions and business requirements.
This factor requires a commitment to constant learning and
a culture of data-driven decision making.
In this video, you learned that data professionals face various challenges
when using generative AI models in multiple industries.
The technical challenges include data quality, model interpretability,
computational resources, and lack of standardization.
The organizational challenges include skill gaps,
integration with existing systems, change management, and measuring ROI.
The cultural challenges include risk aversion, data sharing and
collaboration, trust and transparency issues, and continuous learning.
Successfully navigating these challenges involves a strategic approach to ensure
responsible deployment and transparency. 


## Responsible Generative AI for Data Professionals

Generative AI, including models like GPT-3 or GPT-4, presents both challenges and opportunities. Challenges may include bias and fairness, ethical use, explanation, privacy concerns, and environmental impact.

To address these challenges, responsible AI, which is also referred to as ethical or trustworthy AI, should be implemented, which includes debiasing, diverse dataset curation, and continuous monitoring for biases.

- Responsible AI:

IBM's AI systems are built on five pillars: Explainability, Fairness, Robustness, Transparency, and Privacy. These pillars are crucial for the development, deployment, and usage of AI systems.

Responsible AI encourages transparency and accountability, allowing users to understand decision-making processes and fostering trust in the technology. It also establishes mechanisms to hold developers, organizations, and AI systems accountable for their actions and impacts. Ethical guidelines should be developed and enforced, and industry standards should be established. It is crucial to invest in research to improve model interpretability and provide explanations for generated outputs. Privacy concerns should be addressed by implementing privacy-preserving techniques, such as federated learning or differential privacy.

Collaboration between AI researchers, ethicists, policymakers, and the public is also crucial for creating guidelines and policies for responsible AI development and deployment. User empowerment should be given, and education and awareness about the ethical implications of generative AI should be promoted. Responsible AI allows users to control AI systems, enabling them to make informed decisions about their interactions. This builds public trust in AI technologies, which is crucial for widespread adoption.

- Legal and regulatory compliance_

Responsible AI ensures that AI systems comply with existing laws and regulations, preventing issues associated with unethical practices. Its practices can also guide future regulations and standards in the field.

- Social impact:

Responsible AI is essential for addressing ethical, social, and practical concerns related to the development and deployment of artificial intelligence. It encourages the development of AI systems that contribute positively to society, addressing real-world challenges and promoting the well-being of individuals and communities. It aims to prevent harm, respect human rights, and ensure fair treatment of all individuals. In addition, it promotes inclusive design, avoiding discrimination, and promoting diversity. Environmental impact is another benefit, as responsible AI promotes sustainable and eco-friendly practices in AI research and deployment.

Long-term viability is also crucial, as unethical or irresponsible AI practices can lead to public backlash, legal actions, and restrictions, hindering the long-term viability of AI technologies.

Responsible AI practices include transparency, inclusivity, continuous monitoring, collaboration, user empowerment, education and awareness, and legal and regulatory compliance. Transparency about the capabilities and limitations of generative AI models, inclusive representation in training data, and active stakeholder input are essential.

Adhering to existing and emerging regulations related to AI and advocating for responsible AI legislation is essential for the development and deployment of generative AI models that align with ethical principles and societal values.

- Further reading:

        https://www.ibm.com/blog/3-key-reasons-why-your-organization-needs-responsible-ai/
        https://www.ibm.com/downloads/cas/NK0J1VEN


## CASE STUDY: Considerations While Using Generative AI in Healthcare

- OVERVIEW

A team of data professionals at a leading healthcare company is harnessing the power of generative AI to address critical challenges in data augmentation, diagnostics, drug design, and personalized healthcare. However, each task presents some unique considerations and challenges. Let's look at the issues the data professionals faced and the steps they took for resolution.

- DATA AUGMENTATION

1. Data quality and relevance: Generative AI models require high-quality, relevant data to generate realistic and meaningful augmented data. The team established rigorous data quality control measures and collaborated with external sources to ensure data integrity.

2. Data diversity: To avoid overfitting and enhance generalizability, the team employed generative AI models that could capture the diversity and nuances of the original data. They implemented techniques like adversarial training to generate data with diverse patterns and characteristics.

3. Privacy considerations: Preserving patient privacy is paramount in healthcare data augmentation. The team implemented federated learning and differential privacy techniques to protect sensitive patient information while enabling data sharing and collaboration.

Data professionals' approach:

1. Maintaining data fidelity: The team carefully evaluated the generated data to ensure it preserved the statistical properties and characteristics of the original data, preventing the introduction of artificial biases or distortions.

2. Domain expertise: The team collaborated closely with domain experts, such as clinicians and researchers, to ensure the generated data aligned with clinical relevance and real-world scenarios.

- DIAGNOSTICS

1. Data integration and harmonization: Disease diagnosis often involves analyzing diverse data sources, including medical images, patient history, and lab results. The team developed data harmonization and integration frameworks to streamline data access and analysis.

2. Explainability and interpretability: Explainable AI algorithms are crucial for gaining trust in AI-powered diagnostic tools. The team employed techniques like saliency maps and LIME (Local Interpretable Model Explanations) to provide insights into the AI models' decision-making process.

3. Clinical validation: AI-based diagnostic tools must be validated against traditional diagnostic methods to ensure accuracy and reliability. The team conducted rigorous clinical trials to evaluate the performance of their AI models and demonstrate their effectiveness.

Data professionals' approach:

1. Data bias mitigation: The team addressed data bias by carefully selecting and curating their datasets to minimize the presence of biases that could lead to inaccurate diagnoses.

2. Continuous monitoring and improvement: The team established a constant monitoring and improvement process to update and refine the AI models as new data becomes available and clinical practices evolve.

- DRUG DESING

1. Molecular complexity and dynamics: Drug design involves understanding and manipulating complex molecular structures and their dynamic interactions. The team employed generative AI models capable of representing and simulating molecular structures and their interactions.

2. Target specificity and efficacy: Effective drugs must selectively target disease-causing molecules without harming healthy cells. The team used generative AI algorithms to design drug candidates with high target specificity and optimal efficacy.

3. Predictive modeling and virtual screening: Predicting drug properties and potential side effects is crucial before clinical trials. The team developed generative AI models to predict drug properties and perform virtual screening to identify promising drug candidates.

Data professionals' approach:

1. Data availability and quality: The team collaborated with pharmaceutical companies and research institutions to access high-quality molecular data and ensure the data's relevance to the drug discovery process.

2. Computational efficiency: Drug design is a computationally intensive process. The team optimized the AI models to reduce computational time and accelerate the drug discovery pipeline.

- PERSONALIZED HEALTHCARE

1. Patient data privacy and security: Patients must have confidence that their health data is being used responsibly and securely. To address privacy concerns, the team implemented transparent data governance policies, robust data security measures, and clear communication channels with patients.

2. Patient-centered approach: Personalized healthcare requires understanding individual patient preferences and needs. The team involved patients in designing and developing AI-powered tools, ensuring patient-centricity and fostering trust.

3. Clinical decision support and interpretability: AI models should complement, not replace, clinical expertise. The team developed explainable AI algorithms to provide clinicians with insights into the rationale behind AI-generated recommendations, facilitating informed decision-making.

Data professionals' approach:

1. Addressing data bias and fairness: The team carefully evaluated their AI models to identify and mitigate potential biases that could lead to unfair or discriminatory treatment recommendations.

2. Human-AI collaboration and integration: The team emphasized the importance of human-AI collaboration, ensuring that AI-generated recommendations were integrated into clinical workflows while maintaining clinician oversight and expertise.



# WRAP-UP Module 2

## SUMMARY 2

At this point in the course, you know:

- Generative AI tools can be used to create Python code to perform various operations to draw insights from a given data.

- Univariate, bivariate, and multivariate functions are used to analyze data.

- Hal9’s free plan generates a statistical representation of the data and finds missing values.

- Free generative AI tools can be used to get exploratory insights into the relationship between data variables and create correlation matrices, boxplots, and histograms from data.

- Generative AI streamlines the process of creating dashboards by automating intricate design choices.

- Some generative AI-driven frameworks to develop dashboards are Dash, ChatGPT, Tableau AI, and Einstein Copilot, Akkio, Thoughtspot, DataSquirrel, and Sisense.

- The critical aspects of storytelling in data analytics include data visualization, logical organization, contextualization, engaging your audience, anecdotes and examples, audience-centric approach, and call to action.

- Some generative AI-driven frameworks organizations use to create compelling stories include Google Slides with Duet AI, Generative Reports, DesignerBot, ChatGPT, and Google Bard.

- While using generative AI models, data scientists need to look into data, model, and ethical considerations.

- Data professionals face various challenges when using generative AI in multiple industries.

- The challenges can be broadly categorized into technical, organizational, and cultural issues.


## CHEATSHEET 2

### Important Terms

- Data Insights: Data insights are significant and insightful interpretations or findings that come from data analysis. They frequently entail identifying trends, patterns, correlations, or anomalies in a dataset.

- Data Visualization: Data visualization is the use of graphical or visual representations to enhance understanding, analysis, and identification of patterns, trends, or insights within data.

- Dashboard: Dashboard often consist of a collection of charts, graphs, tables, and other visual components used to present data in an easily understood visual format and are practical tools that help individuals and businesses make well-informed decisions.

- Storytelling: Storytelling in data analytics involves transforming raw data into a compelling narrative that helps communicate insights, trends, and patterns in the data, making it easier for stakeholders to make informed decisions.

- Hallucination: It refers to the generation of inaccurate or illogical information by generative AI models due to flawed training data, inappropriate model architectures, and inadequate evaluation methods.

- AI Bias: AI bias refers to systematic inaccuracies or prejudices in AI systems' outcomes, affecting data collection, algorithm design, and model training. Addressing AI bias is crucial for fairness, equity, and ethical use of AI technologies.

- Fairness: Fairness in AI involves treating all individuals or groups equitably without discrimination, avoiding favoritism based on race, gender, ethnicity, or socioeconomic status. This involves identifying biases, promoting transparency, and distributing AI benefits and risks equitably.


### Generative AI Platforms/Tools used in this module

Data Insights:

    hal9
    ChatGPT

Data Visualization:

    Einblick
    Coulmn.ai
    Akkio

Dashboarding:

    ChartPixel

Storyteling:

    Akkio


### Some Generic Prompts

Get the statistical description of the dataset
    
    " Describe dataset "
    
    Ex: Describe dataset (upload the dataset on ChatCSV and then write a prompt)


Identify missing data

    " Write a <…> code to identify <…..> with missing values. "

    Ex: Identify the attributes with missing data 	Write a python code to Identify the columns with missing values (ChatGPT)
    Ex: Identify the attributes with missing data (ChatCSV)


Handling missing values

    " Write a <…> code to replace missing values with <…..> in the dataset "
    " Replace the missing values <…> in the <…> and save the updated dataset "
    
    Ex: Write a python code to replace missing values with mean values in the dataset. (ChatGPT)
    Ex: Replace the missing values with the mean value in the Screen_size_cm column and save the updated dataset. (ChatCSV)


Get different forms of visualizations from different types of attributes

    " Write a <…..>code to create <…..> plots for the attributes <….> against <…..>. "
    
    Ex: Write a Python code to perform the following actions:
    1. Create regression plots for the attributes CPU_frequency, Screen_Size_inch and Weight_pounds against Price.
    2. Create box plots for the attributes Category, GPU, OS, CPU_core, RAM_GB and Storage_GB_SSD against the attribute Price.
