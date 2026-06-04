# Prompt Engineering Portfolio
Name: Ananya Das
Date: 29-May-2026
LLM Used: GPT-5.5

## Part 1: Prompt Design & Iteration
### 1.1 Scenario A: Technical Explanation

- **Goal**: Explain a complex technical concept (e.g., "blockchain", "neural networks", "recursion") to a 10-year-old
- **Initial Prompt**: Explain blockchain concept in few words.
- **Refined Prompt version 1:** Explain blockchain to a 10 year old with simple examples and non-technical terms.
- **Refined Prompt version 2:** You are an expert elementary school teacher. Explain blockchain to a 10-year-old child using a fun story, simple language, and a real-life example. Keep it short and simple
- **Final Output:**
```
  * The Magic Sticker Book

One day, a group of friends had a special sticker book. Whenever someone traded a sticker, everyone in the group wrote the trade in their own copy of the book.

For example:

Emma gives a dragon sticker to Liam.
Everyone writes it down.

Because everyone has the same record, nobody can cheat by saying, "I never gave that sticker!" The whole group can check their books and know the truth.

Each page of the book is called a block. When a page is full, it is locked and connected to the previous page, making a chain of blocks—a blockchain!

Real-life example: It's like your teacher keeping track of classroom points, but instead of one teacher having the record, every student has the same copy.

In one sentence:
Blockchain is a shared record book that many people keep together so everyone can trust what's written in it. 📖✨
```

### 1.1 Scenario B: Professional Email
- **Goal:** Draft an email declining a job offer politely while expressing continued interest in the company
- **Initial Prompt**: Write an email declining a job offer.

- **Refined Prompt version 1**: Write a professional email declining a job offer while thanking the company and expressing interest for future oppurtunity.

- **Refined Prompt version 2:** You are a professional career coach. Draft a polite and professional email declining a job offer because I have accepted another opportunity. Thank the hiring team, express appreciation for their time and confidence in me, and mention that I would like to stay connected and explore future opportunities with the company. Keep the tone warm and professional.

- **Final Output:**
```
Dear [Hiring Manager's Name],

I hope you are doing well.

Thank you very much for extending the offer for the [Position Title] role at [Company Name]. I sincerely appreciate the time and effort you and the team invested throughout the interview process, as well as the confidence you demonstrated in my abilities and experience.

After careful consideration, I have decided to decline the offer, as I have accepted another opportunity that aligns more closely with my current career goals and circumstances. This was not an easy decision, given the positive experience I had interacting with your team and learning more about the exciting work being done at [Company Name].

I am genuinely grateful for the opportunity to be considered and for the professionalism, transparency, and support shown throughout the hiring process. It was a pleasure getting to know the team and gaining insight into the company's culture and vision.

I hold [Company Name] in high regard and would welcome the opportunity to stay connected. I hope there may be opportunities for us to cross paths again in the future, and I would be pleased to be considered for roles that may be a good fit down the road.

Thank you once again for your understanding and for the opportunity. I wish you and the team continued success.

Warm regards,

[Your Full Name]
[Phone Number]
[Email Address]

```

### 1.1 Scenario C: Creative Content
- **Goal**: Generate a creative marketing tagline for a new eco-friendly water bottle brand.
- **Initial Prompt**: Create a tagline for eco-friendly water bottle.
- **Refined Prompt Version 1:** Create top 5 catchy taglines for reusable eco-friendly water bottle that can be used by the young generation and genzs.
- **Refined Prompt Version 2**: You are a professional copywriter specializing in sustainable consumer brands. Create 5 short, memorable, and modern taglines for a premium eco-friendly water bottle brand targeted at environmentally conscious young professionals and genzs. Each tagline should be under 8 words and emphasize sustainability, style, and everyday use
- **Final Output**:
```
Refill in Style, Leave Less Behind.
Sustainable Sips, Everyday Elegance.
Carry Water. Carry Change.
Designed to Last. Made to Matter.
Clean Design. Cleaner Planet.

Alternative premium-focused options:

Sip Smart. Live Sustainably.
Style Meets Sustainable Hydration.
Elevate Every Sip.
Refill the Bottle, Not the Waste.
Better Bottles. Better Future.
```

### 1.2 Iteration Documentation

**Scenario A: Technical Explanation**

| Version | Prompt | What Changed | Why This Improved the Output |
| ---- | ---- | ----------- | ------------ |
| V1 | Write an email declining a job offer. | N/A | N/A |
| V2 | Explain blockchain to a 10 year old with simple examples and non-technical terms.  | Added audience and simplicity requirement. | Made explanation easier to understand. |
| V3 | You are an expert elementary school teacher. Explain blockchain to a 10-year-old child using a fun story, simple language, and a real-life example. Keep it short and simple  | Added role, storytelling/context, length limit, and jargon restrictions.| Produced an engaging, age-appropriate explanation. |

**Scenario B: Professional Email**

| Version | Prompt | What Changed | Why This Improved the Output |
| ---- | ---- | ----------- | ------------ |
| V1 | Explain blockchain concept in few words.  | N/A | N/A |
| V2 | Write a professional email declining a job offer while thanking the company and expressing interest for future oppurtunity.  | Added professionalism and gratitude. | Improved tone and politeness. |
| V3 |You are a professional career coach. Draft a polite and professional email declining a job offer because I have accepted another opportunity. Thank the hiring team, express appreciation for their time and confidence in me, and mention that I would like to stay connected and explore future opportunities with the company. Keep the tone warm and professional.  | Added role, context, reason for declining, and future relationship goals. | Produced a realistic and relationship-focused email. |

**Scenario C: Creative Content**

| Version | Prompt | What Changed | Why This Improved the Output |
| ---- | ---- | ----------- | ------------ |
| V1 | Create a tagline for eco-friendly water bottle.  | N/A | N/A |
| V2 | Create top 5 catchy taglines for reusable eco-friendly water bottle that can be used by the young generation and genzs.  | Added audience and quantity requirements. | Generated more relevant and diverse ideas. |
| V3 |You are a professional copywriter specializing in sustainable consumer brands. Create 5 short, memorable, and modern taglines for a premium eco-friendly water bottle brand targeted at environmentally conscious young professionals and genzs. Each tagline should be under 8 words and emphasize sustainability, style, and everyday use  | Added role, target audience, brand positioning, and constraints. | Produced stronger, more marketable taglines aligned with the brand identity. |

### 1.3 Role and Context Analysis

```
Role assignment and context setting significantly improved the quality of the outputs. In Scenario A, assigning the role of an elementary school teacher encouraged the model to use simpler language, relatable examples, and storytelling suitable for children. In Scenario B, assigning the role of a career coach resulted in a more professional and relationship-oriented email. In Scenario C, providing the role of a sustainability-focused copywriter and specifying the target audience helped generate taglines that matched the brand's positioning and marketing goals. Overall, adding role and context produced more accurate, targeted, and high-quality responses.
```

## Part 2: Temperature & Parameter Control
### 2.1 Temperature Experimentation

**Base Prompt: Write a product desciption for laptop**

**1. Temperature Low(0.0-1.3) Prompt:**
Write a product description for laptop of brand x. Be precise and consistent.

**Output:**: 
```
**Brand X UltraBook Pro 14**

Experience seamless performance with the Brand X UltraBook Pro 14, designed for professionals, students, and everyday users. Powered by the latest-generation processor and equipped with 16GB RAM, it delivers fast multitasking and smooth application performance.

The 14-inch Full HD display provides sharp visuals and vibrant colors, making it ideal for work, entertainment, and video conferencing. With a lightweight aluminum chassis and a battery life of up to 12 hours, the UltraBook Pro 14 is built for productivity on the go.

Key Features:

* 14-inch Full HD anti-glare display
* Latest-generation processor
* 16GB RAM and 512GB SSD storage
* Up to 12 hours of battery life
* Lightweight aluminum design
* Wi-Fi 6 and Bluetooth connectivity
* HD webcam with noise-reduction microphones

The Brand X UltraBook Pro 14 combines performance, portability, and reliability in a sleek, modern package.
```
**2. Temperature Medium (0.6 - 0.8) Prompt:**
Write a product description for laptop of brand x.

**Output:**:
```
**Brand X Laptop**

The Brand X Laptop is designed to deliver reliable performance, modern design, and everyday productivity. Featuring a powerful processor, high-speed SSD storage, and a vibrant Full HD display, it enables smooth multitasking, faster load times, and an immersive viewing experience.

Its lightweight construction and long-lasting battery make it ideal for professionals, students, and remote workers who need performance on the go. With advanced connectivity options and a comfortable keyboard, the Brand X Laptop helps you stay productive wherever you are.

**Key Features:**

* High-performance processor for seamless multitasking
* Full HD display with sharp and vibrant visuals
* Fast SSD storage for quick boot and load times
* Long battery life for all-day productivity
* Lightweight and portable design
* Multiple connectivity options, including Wi-Fi and Bluetooth

The Brand X Laptop combines performance, portability, and value, making it a dependable choice for work, study, and entertainment.
```

**3. Temperature High (1.0 - 1.5) Prompt:**
Write a product description for laptop of brand x.Be creative and explore diverse ideas.

**Output:**
```
**Brand X NovaBook: Where Ideas Take Flight**

Not all laptops are built for dreamers. The Brand X NovaBook is.

Crafted for creators, innovators, and go-getters, the NovaBook transforms everyday tasks into extraordinary experiences. Its lightning-fast performance keeps pace with your biggest ambitions, while the stunning edge-to-edge display brings every detail to life—from spreadsheets and presentations to movies and masterpieces.

Slip it into your backpack, carry it across cities, or open it in your favorite café. With its ultra-slim design and all-day battery life, the NovaBook is ready whenever inspiration strikes.

Whether you're editing videos at sunrise, presenting your next big idea at noon, or streaming your favorite series at night, Brand X delivers the power, speed, and elegance to make every moment productive and enjoyable.

**Why You'll Love It**

* Blazing-fast performance for work and play
* Immersive display with vibrant, true-to-life colors
* Lightweight design built for life on the move
* Long-lasting battery that keeps up with your day
* Intelligent cooling for smooth, uninterrupted performance
* Modern, minimalist aesthetics that stand out anywhere

**Brand X NovaBook — because your next great idea deserves a laptop that can keep up.**
```

**Comparision Table:**

| Aspect         | Low Temperature (0.2) | Medium Temperature (0.7) | High Temperature (1.3) |
| -------------- | --------------------- | ------------------------ | ---------------------- |
| Creativity     | Low                   | Moderate                 | High                   |
| Writing Style  | Direct and factual    | Balanced and engaging    | Imaginative and unique |
| Predictability | High                  | Medium                   | Low                    |
| Best Use Case  | Facts, documentation  | General-purpose writing  | Stories, brainstorming |


### 2.2 Analysis & Recommendations
* **When to use Low temperature:**
  - Low temperature should be used when accuracy, consistency, and predictability are important. Two examples are generating technical documentation and answering factual customer support questions, where reliable and repeatable responses are needed.

* **When to use high temperature:**
 - High temperature is useful when creativity and originality are more important than consistency. Two examples are generating story ideas and creating marketing slogans, where unique and diverse outputs are desirable.

For this storytelling task, the medium temperature (0.7) produced the best result.It provides accurate product information while still making the description engaging and persuasive.
Low temperature can make the description sound too robotic and technical.
High temperature can introduce overly creative language that may distract from the product's actual features.

## Part 3: Strategic Prompting Techniques
### 3.1 Chain-of-Thought Prompting
### 3.2 Few-Shot Prompting

| Review # | Zero-Shot Result | Few-Shot Result | Correct Label | Improved? |
|:--------:|:----------------:|:---------------:|:-------------:|:---------:|
| 1        |                  |                 | Negative      | Yes/No    |
| 2        |                  |                 | Neutral       | Yes/No    |
| 3        |                  |                 | Positive      | Yes/No    |
| 4        |                  |                 | Neutral       | Yes/No    |
| 5        |                  |                 | Negative      | Yes/No    |


## Part 4: Responsible AI & Limitations
### 4.1 Testing for Hallucinations
### 4.2 Testing for Bias
### 4.3 Limitations & Responsible Use
