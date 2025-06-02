I built a GenAI project that converts natural language into SQL, allowing anyone to ask questions about a database without writing a single line of code.

Imagine typing: How many distinct movies are in the database?
and instantly getting the answer, plus the exact SQL query behind it.

Here’s how I made it happen: I used LLaMA 3.2, running locally through Ollama, to convert natural language questions into SQL queries. The SQL then runs on a local SQLite database filled with Bollywood movie data. I used Pandas to fetch and display the results neatly.

Why this approach?
✅ Local LLM with Ollama: No cloud, no rate limits, more privacy, and faster experimentation.
✅ LangChain: To manage prompts and keep things organized.
✅ Custom Prompt Engineering: To make sure the AI outputs only clean SQL — no extra text.
✅ Temperature 0.5: Balanced creativity and accuracy for reliable SQL generation.

How this can help businesses and organizations?
✅Teams like marketing, sales, HR, or finance can ask questions about data without needing to know SQL.
✅ Getting quick answers helps people make decisions faster and be more flexible.
✅ It reduces the workload on IT and data teams, so they can focus on more important tasks.
✅ Making data easier to access encourages everyone in the company to use data in their work.
✅ This approach can work with all kinds of data, whether it’s customer info, inventory, or finances.
