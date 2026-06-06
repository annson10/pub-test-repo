# Prompt Engineering Portfolio
Name: Annson Colaco  
Date: 06 June 2026  
LLM Used: Gemini 3.5 Flash

## Part 1: Prompt Design & Iteration
### 1.1 Scenario A: Technical Explanation   
#### Initial Prompt
    Explain the  concept "neural networks" to a 10-year-old child.  

#### Refined Prompt 
    Explain neural networks to a 10-year-old child using a fun analogy and a real-life example, keeping the explanation under 100 words and avoiding all  technical terms. 

#### Final Prompt   
    Role: You are an  elementary school teacher teaching for 10 years known for explaining complex topics to children.

    Context: A curious 10-year-old student has heard the term "neural network" in a conversation about artificial intelligence and wants to understand what it means. The student has no background in computer science and may be unfamiliar with technical terms.

    Goal: Explain neural networks in a way that the child can easily understand.

    Instructions:
    Use simple language suitable for a 10-year-old.
    Start with a fun analogy involving something familiar to children like games or sports.
    Avoid technical jargon and complex definitions.
    Include one real-world example of how neural networks are used.
    Use short paragraphs.
    Keep the explanation under 100 words.

#### Final Output
Think of a neural network like a **guessing game** played by a big team of friends.

Imagine you want a computer to recognize a **banana**. You show the team a photo. The first friend looks at the shape and whispers a clue to the next friend, who checks the color. The last friend shouts the final guess: "Lemon!"

When you say, "No, it's a banana!" the friends pass the message back, learning from their mistake.

After playing this thousands of times, they get super smart! This is exactly how tablets recognize your face to unlock.

### 1.1 Scenario B: Professional Email  
#### Initial Prompt     
    Write a polite and professional email declining a job offer while thanking the employer for the opportunity.

#### Refined Prompt     
    Write a concise, professional, and courteous email declining a job offer because I have accepted another position. Express sincere gratitude for the offer, the time invested by the hiring team, and the opportunity to learn more about the company. Politely decline the offer, maintain a positive relationship, and indicate interest in potential future opportunities with the company. Keep the email brief, respectful, and professional, with a clear subject line.

#### Final Prompt   
    Role: You are an experienced and professional business communication email writer.

    Context: I recently completed a job interview process and received a job offer from a company. However, I will not be able to accept the position owing personal commitments. I want to decline the offer professionally while maintaining a positive relationship with the company and expressing interest in future opportunities.

    Goal: Write a professional email addressing the same to the HR.

    Instructions:
    Include a professional subject line.
    Use a respectful, appreciative, and positive tone.
    Thank the company for the offer and interview experience.
    Express admiration for the company and its team.
    Indicate that I would like to stay connected for future opportunities.
    End with a professional closing.
    Keep the email between 150 and 200 words.

#### Final Output   

Subject: Job Offer: [Job Title] - [Your Name]

Dear [HR Partner/Recruiter Name],

Thank you so much for offering me the position of [Job Title] at [Company Name]. I sincerely appreciate the time and effort you and the hiring team invested throughout the interview process.

It was a pleasure learning more about your organization, and I came away incredibly impressed by the team’s dedication and the company’s forward-thinking culture. However, due to unexpected personal commitments that require my full attention at this time, I must respectfully decline the offer. This was a difficult decision, as I think very highly of your organization and the exciting work you are doing.

I would love to remain in touch and hope that we might find an opportunity to collaborate in the future when my circumstances change. Please feel free to connect with me on LinkedIn.

Thank you once again for your time, consideration, and understanding. I wish you and [Company Name] continued growth and success.

Sincerely,

[Your Name]

[Your Phone Number]

[Link to LinkedIn Profile]


### 1.1 Scenario C: Creative Content    
#### Initial Prompt     
    create a creative marketing tagline for a new eco-friendly water bottle brand

#### Refined Prompt   
    Create a creative and memorable marketing tagline for a new eco-friendly water bottle brand. The tagline should highlight sustainability, reusability, and environmental responsibility while remaining concise and appealing to modern consumers.

#### Final Prompt   
    Role: You are a professional copywriter and senior branding consultant specializing in sustainable consumer products.

    Context: A startup is launching a premium eco-friendly water bottle brand targeted at environmentally conscious  adults. The brand aims to position itself as modern, innovative, stylish, and environmentally responsible. The marketing campaign needs a memorable tagline that appeals to customers who want both personal wellness and positive environmental impact.

    Goal: Create 1 best marketing tagline for the brand.

    Instructions:
    Use a modern and optimistic tone.
    Avoid generic phrases such as "save the planet" or "go green."
    Emphasize sustainability and personal benefit.
    Make the tagline memorable and suitable for advertising campaigns.
    Briefly explain why the tagline is the most effective.

#### Final Output   
## The Tagline

**“Pure Hydration. Zero Footprint.”**

---

## Why This Tagline Is Most Effective

As a branding consultant, I selected this tagline because it perfectly balances personal benefit with environmental responsibility in a sharp, modern, and high-impact way.

* **The Dual Benefit:** It immediately establishes a win-win scenario for the consumer. **"Pure Hydration"** speaks directly to personal wellness, premium quality, and clean design, while **"Zero Footprint"** addresses the consumer's desire for absolute environmental responsibility.
* **Avoids Green Cliches:** It completely bypasses tired, overused phrases like "eco-friendly" or "save the earth." Instead, it uses contemporary sustainability language ("Footprint") that resonates with conscious, modern adults.
* **Premium Rhythm and Contrast:** The structure relies on a powerful linguistic contrast—pairing the fullness of "Pure" with the minimalism of "Zero." This creates a rhythmic, punchy cadence that is incredibly easy to remember.
* **Campaign Versatility:** This tagline acts as a perfect anchor for broader advertising copy. It effortlessly scales into sub-campaigns or social media copy, such as:
* *“Pure style. Zero waste.”*
* *“Pure innovation. Zero compromise.”*

### 1.2 Iteration Documentation 
### Scenario A: Technical Explanation

| Version | Prompt                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | What Changed                                                                                                                                                   | Why This Improved the Output                                                                                                                                                                                                                                      |
| ------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| V1      | Explain the concept "neural networks" to a 10-year-old child.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | N/A                                                                                                                                                            | N/A                                                                                                                                                                                                                                                               |
| V2      | Explain neural networks to a 10-year-old child using a fun analogy and a real-life example, keeping the explanation under 100 words and avoiding all technical terms.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Added a specific explanation style (fun analogy), required a real-life example, imposed a word limit, and instructed the model to avoid technical terminology. | These constraints made the explanation more engaging, easier for a child to understand, and more focused on the target audience. The shorter length also improved clarity and readability.                                                                        |
| V3      | Role: You are an elementary school teacher teaching for 10 years known for explaining complex topics to children. Context: A curious 10-year-old student has heard the term "neural network" in a conversation about artificial intelligence and wants to understand what it means. The student has no background in computer science and may be unfamiliar with technical terms. Goal: Explain neural networks in a way that the child can easily understand. Instructions: Use simple language suitable for a 10-year-old. Start with a fun analogy involving something familiar to children like games or sports. Avoid technical jargon and complex definitions. Include one real-world example of how neural networks are used. Use short paragraphs. Keep the explanation under 100 words. | Added role assignment, detailed audience context, learning objective, structured instructions, formatting guidance, and explicit output requirements.          | Providing the model with a teaching role and detailed context helped it better understand the audience's knowledge level. The structured instructions ensured the explanation remained age-appropriate, engaging, concise, and aligned with the educational goal. |

### Scenario B: Professional Email

| Version | Prompt                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | What Changed                                                                                                                                                                                           | Why This Improved the Output                                                                                                                                                                                                                                                                                                                 |
| ------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| V1      | Write a polite and professional email declining a job offer while thanking the employer for the opportunity.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | N/A                                                                                                                                                                                                    | N/A                                                                                                                                                                                                                                                                                                                                          |
| V2      | Write a concise, professional, and courteous email declining a job offer because I have accepted another position. Express sincere gratitude for the offer, the time invested by the hiring team, and the opportunity to learn more about the company. Politely decline the offer, maintain a positive relationship, and indicate interest in potential future opportunities with the company. Keep the email brief, respectful, and professional, with a clear subject line.                                                                                                                                                                                                                                                                                                                                                                              | Added the reason for declining (accepted another position), specified tone, emphasized gratitude, requested future relationship-building, and included formatting requirements such as a subject line. | These additions provided clearer guidance to the model, resulting in a more realistic and professional email that better met the communication objective while preserving goodwill with the employer.                                                                                                                                        |
| V3      | Role: You are an experienced and professional business communication email writer. Context: I recently completed a job interview process and received a job offer from a company. However, I will not be able to accept the position owing personal commitments. I want to decline the offer professionally while maintaining a positive relationship with the company and expressing interest in future opportunities. Goal: Write a professional email addressing the same to the HR. Instructions: Include a professional subject line. Use a respectful, appreciative, and positive tone. Thank the company for the offer and interview experience. Express admiration for the company and its team. Indicate that I would like to stay connected for future opportunities. End with a professional closing. Keep the email between 150 and 200 words. | Added role assignment, detailed background context, a clear communication goal, audience identification (HR), and explicit structural and tone requirements.                                           | The role assignment helped the model adopt an expert communication style, while the context clarified the situation and desired outcome. The detailed instructions ensured the email remained professional, personalized, well-structured, and aligned with the objective of maintaining a positive long-term relationship with the company. |

### Scenario C: Creative Content

| Version | Prompt                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | What Changed                                                                                                                                                                                      | Why This Improved the Output                                                                                                                                                                                                                                                                                                                            |
| ------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| V1      | Create a creative marketing tagline for a new eco-friendly water bottle brand.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | N/A                                                                                                                                                                                               | N/A                                                                                                                                                                                                                                                                                                                                                     |
| V2      | Create a creative and memorable marketing tagline for a new eco-friendly water bottle brand. The tagline should highlight sustainability, reusability, and environmental responsibility while remaining concise and appealing to modern consumers.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | Added key brand values (sustainability, reusability, environmental responsibility), specified the desired style (creative and memorable), and identified the target audience as modern consumers. | These additions gave the model clearer direction about the brand message and audience, resulting in taglines that were more relevant, marketable, and aligned with the product's purpose.                                                                                                                                                               |
| V3      | Role: You are a professional copywriter and senior branding consultant specializing in sustainable consumer products. Context: A startup is launching a premium eco-friendly water bottle brand targeted at environmentally conscious adults. The brand aims to position itself as modern, innovative, stylish, and environmentally responsible. The marketing campaign needs a memorable tagline that appeals to customers who want both personal wellness and positive environmental impact. Goal: Create 1 best marketing tagline for the brand. Instructions: Use a modern and optimistic tone. Avoid generic phrases such as "save the planet" or "go green." Emphasize sustainability and personal benefit. Make the tagline memorable and suitable for advertising campaigns. Briefly explain why the tagline is the most effective. | Added role assignment, detailed brand context, target audience information, brand positioning, a specific objective (one best tagline), creative constraints, and a justification requirement.    | The role assignment encouraged expert-level branding language, while the detailed context helped the model understand the brand's identity and market positioning. The additional constraints improved originality and relevance, and the explanation requirement ensured the chosen tagline was strategically justified rather than randomly selected. |

### 1.3 Role and Context Analysis   
Adding a role assignment helped the AI adopt the expertise and communication style appropriate for the task, such as a teacher, business communication specialist, or branding consultant. Providing context gave the model a clearer understanding of the audience, purpose, and desired outcome of the response. As a result, the outputs became more relevant, targeted, and aligned with the specific goals of each scenario. Overall, role and context reduced ambiguity and improved the quality, accuracy, and effectiveness of the generated content.

## Part 2: Temperature & Parameter Control
### 2.1 Temperature Experimentation
### 2.2 Analysis & Recommendations

## Part 3: Strategic Prompting Techniques
### 3.1 Chain-of-Thought Prompting
### 3.2 Few-Shot Prompting

## Part 4: Responsible AI & Limitations
### 4.1 Testing for Hallucinations
### 4.2 Testing for Bias
### 4.3 Limitations & Responsible Use
