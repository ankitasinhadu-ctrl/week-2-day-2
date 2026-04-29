🤖 Prompt Engineering Lab — TechFlow Solutions Chatbot Fix

What is this project?

This project is a hands-on lab where I acted as an AI consultant hired to fix a broken customer service chatbot for a fictional company called TechFlow Solutions. The chatbot had one big problem — it gave a different style of answer every single time it was asked the same question, which made it completely unreliable for real use. To fix this, I worked on three specific tasks: figuring out whether a customer message is positive, negative, or neutral (Sentiment Analysis), writing consistent product descriptions from basic product info (Product Description Generation), and pulling out key details like order numbers and dates from customer messages (Data Extraction). I tested each task by running the same prompt 5, 10, and then 15 times and measuring how often the AI gave the same style of answer — a score I called the "consistency percentage." The starting prompts scored very low, proving that simple instructions alone are not enough when you need an AI to behave reliably at scale.
What techniques did I use and what did I learn?

To improve the prompts, I went through three versions. The first version was a basic instruction with no rules — it worked sometimes but was very unpredictable. The second version added clear format rules, like telling the AI to reply with exactly one word or always return a JSON object, which improved the consistency score noticeably. The third and best version used two powerful techniques — few-shot prompting, which means showing the AI 2-3 examples of exactly what a good answer looks like before asking the real question, and Chain-of-Thought prompting, which means asking the AI to think through the problem step by step before writing its final answer. These two techniques pushed the consistency score above 80% for all three tasks, which was the target goal. The biggest lesson from this project is that the quality of an AI's output depends almost entirely on the quality of the instructions you give it — and the best way to write good instructions is to test them many times, measure the results, and keep improving, just like any other engineering problem.


📁 Tech used: Python · Jupyter Notebook · OpenAI API (gpt-4o-mini)
💡 Best for: Beginners learning prompt engineering, AI enthusiasts, anyone building chatbots or AI-powered tools
