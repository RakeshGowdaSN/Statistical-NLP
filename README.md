# Statistical-NLP
## Part 1:
• DOMAIN: Digital content management

• CONTEXT: Classification is probably the most popular task that you would deal with in real life. Text in the form of blogs, posts, articles,
etc. is written every second. It is a challenge to predict the information about the writer without knowing about him/her. We are going to
create a classifier that predicts multiple features of the author of a given text. We have designed it as a Multi label classification problem.

• DATA DESCRIPTION: Over 600,000 posts from more than 19 thousand bloggers The Blog Authorship Corpus consists of the collected
posts of 19,320 bloggers gathered from blogger.com in August 2004. The corpus incorporates a total of 681,288 posts and over 140 million
words - or approximately 35 posts and 7250 words per person. Each blog is presented as a separate file, the name of which indicates a
blogger id# and the blogger’s self-provided gender, age, industry, and astrological sign. (All are labelled for gender and age but for many,
industry and/or sign is marked as unknown.) All bloggers included in the corpus fall into one of three age groups:
• 8240 "10s" blogs (ages 13-17),
• 8086 "20s" blogs(ages 23-27) and
• 2994 "30s" blogs (ages 33-47)
For each age group, there is an equal number of male and female bloggers.
Each blog in the corpus includes at least 200 occurrences of common English words. All formatting has been stripped with two exceptions.
Individual posts within a single blogger are separated by the date of the following post and links within a post are denoted by the label url
link. Link to dataset: https://www.kaggle.com/rtatman/blog-authorship-corpus

• PROJECT OBJECTIVE: The need is to build a NLP classifier which can use input text parameters to determine the label/s of the blog.

## Part 2
• DOMAIN: Customer support

• CONTEXT: A new Edutech company has a an academic support department which receives numerous support requests every day throughout the
year. Teams are spread across geographies and try to provide support round the year. Sometimes there are circumstances where due to
heavy workload certain request resolutions are delayed, impacting company’s business. Some of the requests are very generic where a
proper resolution procedure delivered to the user can solve the problem. Company is looking forward to design an automation which can
interact with the user, understand the problem and display the resolution procedure [ if found as a generic request ] or redirect the request
to an actual human support executive if the request is complex or not in it’s database.

• DATA DESCRIPTION: A sample corpus is attached for your reference. Please enhance/add more data to the corpus using your linguistics
skills.

• PROJECT OBJECTIVE: Design a python based interactive semi - rule based chatbot which can do the following:
1. Start chat session with greetings and ask what the user is looking for.
2. Accept dynamic text based questions from the user. Reply back with relevant answer from the designed corpus.
3. End the chat session only if the user requests to end else ask what the user is looking for. Loop continues till the user asks to end it.
