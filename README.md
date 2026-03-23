# Loop-UX-Assessment
Candidate - Kayla Sadler

Role - UI/UX Engineer/Product Designer

Submitted: March 23, 2026

View my work

Deliverables and Links

Figjam - User journey: https://www.figma.com/board/dZw3K5yHqGbmvIkcl0HNfi/User-Journey?node-id=0-1&t=ReBzoYJsC0Gv7JEz-1

Figma File - Wireframe mockups and annotations: https://www.figma.com/design/95wLG9vqjKyiABkgEsdRMq/Wireframes?node-id=0-1&t=Qo6UgJxUhTFQXV7v-1

Loom Video: 

# What I did

I built a UX package for an enterprise security and compliance portal. This tool is a product or software that an IT Security Analyst might log into everyday to track alerts, company security health, and make sure everything is logged for audits.

The package includes:

- A user flow diagram mapping a specific part of the user's daily workflow.
- 4 annotated wireframe mockups with some engineering notes
- A list of example reusable UI components and user behavior and interaction patterns
- This README, an AI-usage note, and a Loom video

# The User

The scenario:

Jamie is an IT Security Analyst at a mid-size company. She does not write code. Her job is to make sure the company doesn't get breached, fined, or embarrassed — and to prove to auditors that she stayed on top of it.

Jamie logs in every morning at 8:45 AM with one question: did anything bad happen overnight?

Jamie logs in and sees unauthorized access attempts in the middle of the night. She needs to know are the attempts still happening? Did the attempts succeed or fail? What systems are affected and what are Jamie's next steps? She needs to be able to access this information quickly and be able to take care of it right away or escalate it to the necessary person within her company.

# Assumptions

Before diving into design, I made a few assumptions:

- For the sake of this task, I focused on one user specifically. In a real-world scenario, a product like this would have many different users, all with differing responsibilities and requirements out of the software. I scoped to the analyst because they are the daily active user.
- Desktop only. Users are probably at work or at their desk...no one is going to handle critical alerts on their mobile phone.
- The portal surfaces a lot of data. There is a lot going on behind the scenes, so for this task, I assumed backend data handling would be in the underlying software, and Jamie does not need to see most of that stuff. Her role as an analyst is well-defined.
- A big assumption I made is that research has already been done. I treated Jamie as a user persona that we have already interviewed, observed, surveyed, and validated. Anything about this scenario I have created we can assume has been researched, reviewed, and is true.
- There were limited or no constraints as to what was possible in regards to the engineering and development teams. For this task, I assumed that anything was possible and had the creative freedom to come up with features regardless of if it could be developed within scope.

# Major Tradeoffs

I designed one user's core daily flow rather than sketching a wider system shallowly. An enterprise portal could realistically have 50+ screens.

For the sake of time in this task, I did not think about edge cases and component states. A product this large would have many different states, like empty states, hover states, error and success states, etc. 

One major tradeoff for this task is that I did not have a design system to work off of. My experience and expertise is creating design systems that are scalable, and help designers and engineers create consistency within the product, so that users can rely and have trust within the software that they are using. In a real scenario, I would help design and craft a workable, scalable design system, both in Figma and in frontend code, to help create the product. I would work with OKLCH colors schemes, brand colors, typography, spacing and radius tokens, and reusable components to create a design system that works. I did not think about designing within a system for this task.

# What I Would Do With More Time

I would build out a full working prototype of this user journey using frontend code or Figma's prototyping features. This lets stakeholders and engineers see exactly how the product should behave with a "real" user working within it. This can also help see any edge cases or constraints that may have been missed within the designing phase.

I would define responsive behavior. What happens when the screen is only 1280px? 764px on a tablet? What would it look like on a very large monitor?

With more time, I would design a design system to work out of. I am proficient with designing in Figma, and am able to create full design systems using Figma's variables and token features. I could also design a design system in frontend code using HTML, CSS, React and Javascript, but this would take me a little longer than Figma.

# AI Usage Note

Tools Used:
- Figma
- Claude
- Figma Make
- Loom

Where AI helped:

I used Claude to help me understand the scope of the task and what it was asking me to do. I had Claude generate a user for me (Jamie) and help me walk through one of her daily workflow journeys.

I used Claude to help me generate some initial ideas for wireframes and mockups, and then I had Claude come up with prompts to put into Figma Make to quickly get a workable wireframe within Figma, compelete with autolayouts and frames that I could iterate and correct.

Where AI was not helpful:

- Claude's initial suggestion included a full multi-role system.  I rejected this scope because one role done well demonstrates more than three roles done shallowly, plus I had the constraint of time
- Figma Make repeatedly defaulted to dashboard layouts regardless of prompt — I had to rewrite prompts multiple times and attach reference screenshots to get the alert detail and assignment screens right
- AI-generated copy for section labels and button text was generic. I rewrote these to reflect clinical enterprise language appropriate for a security context
- The recommended action section was not visually distinct in early AI outputs. I made the deliberate decision to give it a tinted background — AI did not suggest this, I added it based on my understanding of what Jamie needs most from that screen
