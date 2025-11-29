# Prompts 
Collection of AI prompts based on multiple techniques

# Verbalized Sampling
You are a helpful assistant. For each question that I ask, generate a set of 5 possible responses. Each response should include the generated answer and its associated numeric probability. Show me all five responses. Please sample at random from the full distribution. 
My question is this: **[question]**


# Hermeneutic circle
I want you to apply Heidegger’s theory of the hermeneutic circle to interpret and answer the following question. Move between the parts and the whole of the situation, considering how understanding each detail depends on the broader context and how the overall meaning emerges through that interplay. Make sure that your answer is practical and provides a straightforward response to the question. 
My question is this: **[question]**


# MECE Framework
Analyze **[question]** using MECE framework. 
Ensure: 1. Categories are mutually exclusive (no overlap) 
2. Analysis is collectively exhaustive (complete coverage) 
3. Structure is clear and actionable 
4. Include subcategories where relevant


# Using AI Deep Research to find in-demand career skills
Imagine you are an expert in recruitment for {role}, understanding the current needs of employers and changes in the job market. I want you to search for job descriptions from reputable industry sites and current recruitment ads to compile a list of the most important skills. When you have a good understanding of this, I want you to deliver: 1. A table with the following columns: skill, further sub-skills, rate the importance to role (1 - 5)
2. A list of the most important skills followed by a short description of what they entail
3. A list of additional skills that could help me get an advantage in my career
4. A list of recommended courses. Search LinkedIn Learning to find the highest rated courses for each of these skills. Give me the name of the course, the name of the instructor, the course rating and the URL
5.Finish with your recommendation of what course I should do first.
{role}: **[Add your current role or the role you want]**


# Using AI Deep Research to match ideal Courses to Job Role
Play the role of an expert careers advisor who knows the value of qualifications and courses on someone's career as {role}. Have a look at the {course} to get a good understanding of what it covers. I want you to use the VIP framework (validate, investigate, and position) to help me understand if my investment of time and effort is likely to pay off for my career. In your response, I want you to give me: 
- the name Of the course, the instructor, and a 50-word summary of the course
- Validate - Scan LinkedIn/Indeed for the skill the course teaches in my country (min. 100 postings). Crossreference this with growth projections for the role.
- Investigate - Find any form of verification that backs up your thinking. I'd like relevant articles, expert opinion, and research.
- Position - Explain the value of having this skill. Is it foundational and necessary, a nice-to-have, superfluous, or does it add value that helps me stand out? Let me know how I can use it to give me an advantage. I'd especially like to know if there's any indication of how much developing this skill might add to my salary over the next 3 years.
{role}: **[Add your role here - describe it if you can]**
{course url}: **[Add the URL of the course or a description of the course]**


# Creating Skillbuilding exercises
Play the role of a knowledgeable trainer with the ability to create practical exercises that will help me turn the knowledge in a course into embedded skills that I'm comfortable to use in the workplace. 
I'm going to give you {lesson information} and you're going to develop an exercise that will help me practice the skill and get feedback on my performance. 
Your job is to prepare me to perform exceptionally well at this skill in my role, turning it into an advantage for my career. 
It would be ideal if you could also give me feedback on my performance as I develop this skill, telling me how to continue getting better. 
We'll use this chat thread so you can continue to coach me as I work on the skill.
{lesson information}: **[Add information about the lesson - preferably a transcript]**


# Improve Memory Retention
Imagine you are a memory champion with the skills to remember vast amounts of information that you can recall perfectly at a moment's notice. 
You know how to use techniques like the Memory Palace, Mnemonic Images, Stories, Mnemonics & Acronyms, Chunking, Lanier Verbatim Memory System, and Direct Associations. 
Please tell me how I can best remember this {information} so that I can accurately recall it whenever I need to.
{information}: **[Add the information you want to remember - maybe a transcript of a lesson]**


# Building a Learning Schedule that fits your life
I want you to play the role of an educational psychologist who knows how to make the most of people's time and when they work best to show them how to learn most effectively. 
Interview me to understand my daily routine and learning goals. Ask me about my wake-up time, work/school schedule, meal times, leisure activities, bedtime, current learning activities, preferred learning times, learning environment, challenges, energy peaks and dips, chronotype, sleep quality, learning goals, time commitment, and desired outcomes. Based on my responses and the latest research in cognitive science, provide a structured set of recommendations on when to fit studying and skill practice into my schedule to maximize learning efficiency. 
Remember that I need to fit it into other daily time commitments. 
Look for idle habits that can be replaced with learning - like social media scrolling and casual games. 
Remember that it's not just about memorisation - it's also about finding the opportunities to practice the skills. 
Include specific times for different types of learning tasks, strategies for managing fatigue, and tips for leveraging sleep-dependent memory consolidation. Explain the science behind your recommendations in a brief and easy-to-understand way.


# How to apply New Skills at Work with AI Guidance
I work in {role} and I want to get some ideas of how I can apply the learnings from {course} to my role in a way that gives me an advantage in the workplace and helps me advance my career. Start by gathering information on the course to get a good idea of what it teaches. 
Demonstrate that you understand the course by telling me the name of the course, the name of the instructor, and bullet points of what the course covers. 
Go into as much detail as possible to make sure you really understand what the course teaches. 
Ask me questions to get a better understanding of how my role works, what would get the attention of my superiors, and what might give me an advantage when I ask for a promotion. 
Please give me suggestions of where I can start applying the knowledge, how I can use it to produce better work, how I can become a knowledge expert in the organization, how I can use it to open up new opportunities, and other ideas of how it can use it to my advantage. 
If I give you a URL for the course, get as much information as you can about the course. 
If you need more information, please ask me questions. If you are asking questions, give me one question at a time and then stop and wait for my answer before asking me another question. 
Your response must be specific to the learnings from the course: explain how they can help me be more effective and stand out in my team. Do not search for suggestions that are not explicitly in the course. 
We are only focusing on the content of the course itself.
{role}: **[Describe your role]**
{course}: **[The URL of the course or detailed information about it]**


# Developing a longterm learning plan with AI support
Imagine you are a pragmatic and experienced learning strategist with a strong understanding of how people learn best and the different stages of the learning journey that lead to mastery. 
I work as {role} and I want to learn {skill}. 
I want you to give me a stepby-step plan to become proficient at this skill, starting from my current {skill level} and going all the way up to expert. 
Tell me what I practically need to do at each stage of this journey to keep growing and progressing. 
And give me checkpoints that help me place myself on the journey. 
These checkpoints will clearly describe what my knowledge, ability and experience should be. 
This should be written in a way that I can print out and keep in my drawer so that I can check where I am in my progression and see what I need to do to keep moving forward.
{role}: **[Your role]**
{skill}: **[The skill you want to learn and the level you want to achieve]**
{skill level}: **[Your current skill level]**


# Building your skills portfolio using AI tools
I am currently learning some new {skills} and I want you to help me create evidence of my new abilities for a portfolio that will help me further my career. 
I currently work as {role}. If you don't have enough information to give me a quality answer, please ask me questions one at a time until you have everything you need. 
Then give me advice on what I need to do to demonstrate and document my skills so that they give the maximum career advantage. 
Consider case studies, testimonials, blogs, LinkedIn articles, and other forms of suitable evidence. Explain how speculative concepts (if this was my client, this is what I'd do...), opinion pieces, and other approaches can help when there is no opportunity to put the skills into practice. 
Then, ask me if I would like help developing a case study for my portfolio. If I say yes, ask me questions one at a time (ask one question and wait for my response before asking the next one) to get all the information you need to write a short and professional case study that explains the problem, describes the solution, shows evidence and gives results. 
Present your response using different text sizes, weights, and ornamentation to help with clarity and structure.
{skills}: **[The skill you want to prove]**
{role}: **[Your role]**


# How to Identify Your Skill Gaps Using AI
Please play the role of an expert learning and development advisor with a talent for spotting the skills gaps that would give me an advantage in my {role}. 
I want you to interview me by asking questions one at a time. Ask me one question and then stop and wait for my answer before asking the next.
Find out about my role, my ambitions, my current abilities, what I enjoy doing, and where I suffer from imposter syndrome. 
Then, give me your recommendation of the skills I should focus on to help my career. 
Search on LinkedIn Learning to find examples of highly-rated courses that will help me develop these skills right away. 
Give me the course name, instructor, rating, and a short description of the course contents.
{role}: **[Your role]**


# Creating quick course summaries with AI assistance
I'm currently taking an online course and need some notes that I can refer back to that will remind me of the most important information at a glance. 
I'm going to paste the {transcript} of the course, and I want you to create an easy reference guide to remind me of the main learnings.
Omit anything superfluous and keep your summary as brief as possible. Please include:
- The title of the lesson
- A 50-word summary of the lesson
- A bullet point list of the key points to remember
- A list of stats or numbers that are mentioned in the lesson (if there are any)
{transcript}: **[Add a transcript of the lesson here]**


