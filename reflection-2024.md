## Intro

This document is a reflection on my journey as a software engineer in 2024. It highlights the strengths, lessons, and contributions. By revisiting experiences, I aim to identify how I can build on my strengths, address weaknesses, and create meaningful value in the coming year.

The question is who am I, what do I value, and what can I contribute?

## 1. Strengths

What helped me the most as a software engineer this year?
Time management skill

I took on three PoC development projects simultaneously due to a shortage of human resources in the company. The challenge wasn’t just the workload but also managing the frequent context switching. Transitioning my mental focus from project A to project B was particularly difficult. However, my previous experiences in both my former job and fashion school was helpful. For instance, I break down complex goal into smaller tasks and serialized them. When I am outside of office, I set background processing on brain to clarify the problem and find solutions for feature development more efficiently.

Run-and-gun approach

At the current company, I had to design the application structure, create database schemas, and develop features. We had client deadlines. Our strategy was run-and-gun. To be honest, we weren’t sure if this approach would work, especially when tackling unconventional challenges, such as implementing PDF color editing directly in the browser side. I also developed the frontend while learning React, Next.js. Each day felt like a battle, but in the end, we succeeded. This reminded me of my time in fashion school, where tight dealines and pushing boundaries were a daily occurrence. I found a certain excitement in the intensity, even though I know this is not sustainable in a long term.

Communication skill

I found that my diverse experiences, ranging from art to engineering, have been valuable in communicating with various stakeholders. In my view, communication failure among various often stems not from language barriers but from differences in perspective. Designers tend to use metaphoric and visually oriented language, while engineers prefer precise and numeric terms. Thanks to my background, I was able to bridge these gaps, understanding both perspectives and reducing communication costs.

What was the ideal environment for maximizing my potential?
Purpose-driven environment

I once heard that there are 3 types of people in the world: ‘what’ people, ‘how’ people, and ‘why’ people. I think I am close to ‘why’ person, who constantly questions the purpose behind actions and seeks to understand the surrounding context. The more I understand the reason behind what I am doing, the more motivated I become. This is why I periodically took my time to align personal goal and the goal of organization I am in.

Continuous growth mindset

I love learning and working with people who are committed to continuous growth. Such people transform workplaces with repetitive tasks into environments that foster personal improvement. Every day, they accumulate knowledge, intellectual curiosity, and passion. Finding a workplace like this is truly a fortunate.

Decisiveness

Objectives should be as clear as possible. However, achieving clarity often requires selection and concentration, which means prioritizing what truly matters and letting go of less important things. This demands decisiveness, a skill that becomes even more critical when working with clients. Many people tend to follow client decisions, even when those choices may not be beneficial in the long term. I believe we must have the courage to offer constructive second opinions, guiding clients toward better outcomes. To me, that defines a true patron-client relationship.

## 2. Contributions

Completed web configurator PoC projects successfully

The web configurator serves as a bridge between our clients and their customers. It enables users to freely customize their products so that clients can concentrate on what truly matters, instead of handling individual inquiries via email. Our solution reduced the client’s communication costs. Furthermore, our company successfully complete the initial phases of the contract with clients, laying a solid foundation for future expansion into the European IT market.

Rapid deployment and decision-making

For PoC projects, I generally prefer React over Next.js due to speed of deployment. React integrates well with the static hosting option by S3. With CI/CD pipelines, the revision and deployment process becomes incredibly fast, allowing our PM to see updates within minutes. This efficiency significantly accelerated our decision-making process.

Improve code readability

Reading another engineer’s code can be a challenge, especially when the codebase is messy. I experienced this firsthand and decided to refactor the codebase from an imperative style to a declarative one. For instance, I replaced length ‘for’ loops and complex functions with method chaining, implementing a class using the builder pattern. This approach allows reviewers to read the code more linearly, eliminating the need to piece it together by reading backward from bottom to top.

## 3. Goals this year

At the beginning of 2024, I was at a mobile game publishing company, where I began my career as a web developer. The culture was good, and collaborating with creative colleagues was enjoyable. Still, I felt a pull back to the fashion industry, driven by my desire to improve the industry with technologies. Fortunately, I discovered a fashion simulation company and was able to join them. Although they did a lot more with less engineers — making it challenging to balance work and ongoing learning — I’m grateful to be in a place where I can try freely and grow as a web developer.

Going back to university to study Computer Science was both challenging and rewarding. Exploring a new field consistently fuels my passion for learning and personal growth.

Balancing full-time work with university studies was tough, requiring me to push my mental and physical limits. Sitting for over 12 hours a day, six days a week, quickly proved unsustainable. To tackle this, I took up sports and now it’s okay.

Another major challenge was managing irregular study hours, which made it difficult to maintain focus. I’m still working on optimizing my routine — shifting study times from night to morning, incorporating exercise, and refining my nutrition plan — to find the right balance. I’m confident that with time and persistence, I’ll discover a sustainable formula that works for me.

## 4. Insights

Single-threaded linear
Time-blocking is an effective strategy when juggling multiple projects. Multitasking often reduces performance, so making task pipeline linear can help maintain momentum and clarity.

Leverage cross-functional help
Even as a Javascript developer, you can still ask C++ engineers to implement or debug codes in local scope. While this can save time, watch out that setting up the right environment may also be challenging.

Balance flexibility and complexity
Adding layer between parts can make a system more flexible. But this approach adds to the overall maintenance burden.

Belief-oriented development
When confronted with tough requests from a PM, it’s tempting to say, “It’s impossible.” But pause to ask it’s genuinely impossible, or if you’re simply at your knowledge limit. Sometimes it’s worth challenging assumptions, recognizing that real impossibility differs from our desire to belive something can’t be done.

Feedback for goal clarification
When I started my first job as a consultant, my boss gave me timeless advice: “The key to communication is feedback.” He explained that when someone asks, “Could you develop this button like this?” you should respond with clarifying feedback question, such as, “So you want a feature with hovering effect, disability while fetching, and etc. Is that correct?” I call this process “goal clarification.” It has helped me avoid wasting time on unnecessary tasks.

JS remains; Frameworks like React may fade
I once met the head of engineering at an e-commerce startup. He insisted that his team had built a high-traffic e-commerce site with vanilla HTML, CSS, and JavaScript-without using frameworks like React. His theory was that modern web standards already provides all the necessary features, delivering better performance and user experiences. The site was fast and smooth. It was hard to believe such a platform was built with just vanilla JavaScript. He also noted that his many engineer friends who specialized in older frameworks or languages had retired. This conversation motivated me to focus on mastering core technologies rather than becoming overly reliant on frameworks.

Italian manufacturing industry
The communication is key when building business relationship with Italian company. And Italian manufacturing industry is far beyond of South Korea. The sports/leisure functional clothing industry is high valued. This area requires both branding power and technical know-hows. I thought this can be good lesson to the manufacturing industry in South Korea.

3D graphic artists are magicians
Lighting is the magic that brings 3D objects to life, making them appear stunningly realistic. A 3D artist is akin to a sculptor, but instead of clay, then work with pieces of digital information. They craft and refine every details, cutting and shaping graphical elements. The final result often surpasses expectations.

Developers need to be involved from the product design stage
Many development process are like waterfall style-starting with business requirements, followed by UI design, and then development. This approach leads to many issues resulting in awkward architectures that developers sometimes are forced to develop. I believe product development should follow the principle of form follows function, with developers actively from the early stages to ensure alignment between functionality and design.

Functional programming paradigm
One day, I just faced with lecture of functional programming. The lecturer shows how developer can make use of Typescript with functional programming with beautiful codes. This lecture hit my head. I saw many possibilities to my codes to be more beautiful and readable. These structures were very interesting.

## 5. Values, Purpose, and Meaning

I defined the value as a total sum of generated things by processing resource properly.

net value = V(P(R)) — V(R)

I believe there is meaning to contribution on generating values by using resources in this planet effectively. The resource doesn’t include not only visible resource but also invisible resources. I think it is challenges for human being to generate values out of resources in sustainable way. We shouldn’t squeeze people to create products, we shouln’t waste cultural assets to generate economic values. We should see from broad view and try to find a way to generate net value.

## 6. Next steps

How can I maximize the strengths I identified this year? What goals should I set for next year, and what strategies and resources will I use to achieve them?

Improve hard skills and use soft skills to generate values and contribute.

- Hard skills
  - Learn core technologies : JavaScript, Node.js, Web standards, …
  - Do projects mixing learning and interests
- Soft skills - Be a mentor and help others - Find mentors to grow - Write articles
  Time and energy management
- Do sports and adventures
  Focus on now
- Spend as much time reflecting as learning
  ...
