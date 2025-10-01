
# 🧠 Mrunal's AI Agent Portfolio

Welcome to my collection of intelligent automation solutions! I specialize in creating AI agents that streamline workflows, enhance productivity, and transform how businesses handle routine tasks. From content generation to data analysis, each agent is designed to solve real-world problems with precision and efficiency.

---

## About Me

I’m Mrunal, a healthcare product manager with 7+ years of experience building digital solutions that make healthcare more accessible, efficient, and impactful. My mission is simple: deliver the right care, to the right people, at the right time.

I’ve worked across Asia, Africa, and North America, leading initiatives from government-scale health system digitalization to consumer platforms that help patients book tests, monitor conditions, and access care with ease. With a background in IT engineering and an MBA, I bridge the gap between technical possibility and real-world usability—helping teams identify the right problems and design solutions that make an impact.

Beyond my role at LifeLabs, where I manage consumer platforms like MyCareCompass and MyVisit, I also work as an independent consultant. I’ve helped organizations define interoperability specs using FHIR, design UX journeys for digital health startups, and integrate platforms to improve efficiency.

I’m passionate about using technology to reduce administrative burden, improve outcomes, and create healthcare experiences that truly serve patients, providers, and systems alike.

---

## 🚀 Featured AI Agents

### MyTestCompass  
**Description**: My Test Compass is a retrieval-augmented AI assistant designed to give frontline lab technicians instant access to complex test catalog information. Instead of scrolling through hundreds of pages or waiting for supervisor guidance, technicians can simply ask questions in natural language and receive accurate, context-aware answers in seconds.

**Use Case**: Perfect for Lab Technicians and healthcare partners who need quick access to the latest lab test information without searching through multiple systems. Companies can use it to empower users, onboard teams faster, and reduce strain on support staff—all while ensuring answers come directly from trusted product knowledge.


**Key Features:**
- Smart Query Handling: Determines if a question is relevant to lab testing. If not, it politely declines, keeping the interaction focused.
- Contextual Memory: Remembers follow-up questions (e.g., linking “turnaround time” to the previously asked CDT test).
- Retrieval-Augmented Generation (RAG): Connects directly to the LifeLabs test directory vector database, ensuring responses are always grounded in official documentation.
- Interactive Chat Mode: Provides an experience similar to asking a supervisor, but with instant accuracy and consistency.

[🔗 Try it out](https://app.mindstudio.ai/agents/mytestcompass-f9d9b9e5/remix)

[🔗 Demo Recording](https://youtu.be/aU5FlXLa9fY)

---

### Reddit Sentiment Analyzer & Recommendation Agent  
**Description**: An AI-powered agent that searches Reddit for discussions on chosen keywords, extracts relevant threads, and performs sentiment analysis across posts and comments. Beyond just classifying sentiment as positive, negative, or neutral, it also generates actionable recommendations—helping you address negative feedback, improve areas of neutrality, and amplify positive sentiment to strengthen community perception.

**Use Case**: Product and Brand managers can monitor public perception of their products and receive actionable recommendations to improve community sentiment.

**Key Features:**
- Multi-level sentiment: comment → thread → theme → overall 
- Theme clustering: lightweight clustering guided by domain labels so outputs are business-readable.
- Evidence-first: links/quotes included for auditability and trust.
- Prescriptive layer: not just “what people feel,” but what to do next, prioritized by impact.

[🔗 Try it out](https://app.mindstudio.ai/agents/reddit-sentiment-analyzer-d97ed010/remix)

[🔗 Demo Recording](https://youtu.be/eKg9PIfJFS8)

---

### Daily News Digest  
**Description**: The Daily Email Digest Agent delivers a personalized news briefing straight to your inbox every morning, transforming information overload into a concise, actionable newsletter.

**Use Case**: Busy executives, product managers can stay informed and track market / competitor trends without spending hours reading multiple news sources, getting only the most relevant updates.

**Key Features:**
- Automated Scheduling: Runs every day at 8 a.m. (customizable) to ensure timely delivery.
- Live News Retrieval: Searches Google News for a specified topic (e.g., AI Agents) and gathers the top stories.
- Content Normalization: Cleans and reformats JSON data for consistency across multiple articles.
- Deep Article Analysis: Scrapes each story, generates a one-paragraph summary, and extracts key takeaways.
- Professional Newsletter Output: Converts results into polished HTML with thumbnails, headlines, summaries, bullet takeaways, and “Read Full Story” buttons.
- Email Integration: Automatically sends the formatted digest to a chosen email address.

[🔗 Try it out](https://app.mindstudio.ai/agents/daily-news-digest-a6bf32d3/remix)

[🔗 Demo Recording](https://youtu.be/yhR4m5rAvAM)

---

### WebSite Monitor  
**Description**: The Monitor Website Changes Agent automatically tracks updates on any specified webpage and alerts you with a clean, structured report. Designed to run on a schedule, it compares the latest scrape with previous versions and flags only meaningful differences.

**Use Case**: Ideal for competitive intelligence, compliance monitoring, or product updates, this agent removes the manual effort of checking websites for changes. Teams stay informed in near real-time, saving time while ensuring no critical update slips through

**Key Features:**
- Automated Website Scraping: Captures webpage content at regular intervals (default: every 2 days).
- Change Detection: Compares the new scrape with the last stored version to identify differences.
- Smart Reporting: Generates a Markdown-formatted report summarizing detected changes.
- Flexible Notifications: Delivers reports via email or Slack, depending on user preference.
- Efficient Workflow: Ignores unchanged sites to avoid unnecessary noise.

[🔗 Try it out](https://app.mindstudio.ai/agents/website-monitor-927bcbd9/remix)

[🔗 Demo Recording](https://youtu.be/JYn1W4y3tcI)

---

### Research Report Generator  
**Description**: The Research Report Generator Agent automates the end-to-end process of transforming raw online content into professional, structured research reports. It’s designed for knowledge workers, consultants, and analysts who need to synthesize large volumes of information into actionable insights quickly.

**Use Case**: It provides organizations with decision-ready intelligence at a fraction of the time and cost, making it ideal for: Consulting firms preparing industry briefings, Corporate strategy teams monitoring market shifts, Academic and research teams needing synthesized literature reviews.

**Key Features:**
- Automated Research Workflow: Starts with a search query on a chosen topic and pulls in relevant web sources.
- Content Scraping & Analysis: Extracts the full text of each source, then applies AI-powered analysis to distill the most important points.
- Structured Data Output: Normalizes findings into consistent JSON with metadata, summaries, and key takeaways.
- Iterative Compilation: Aggregates multiple article analyses into a single dataset for richer synthesis.
- Report Assembly: Uses AI to format the compiled content into a polished, multi-section research report (executive summary, detailed analysis, key findings, and references).
- Export Flexibility: Can output the final report as structured HTML, text, or formatted assets ready for client deliverables.

[🔗 Try it out](https://app.mindstudio.ai/agents/research-report-generator-agent-7569d706/remix)

[🔗 Demo Recording](https://youtu.be/cjj1WSDHVu8)

---

### FAQ Generator for HomePage  
**Description**: The FAQ Generator Agent creates search-optimized FAQs directly from a webpage’s content. Triggered through the Chrome extension, it scrapes the page, identifies key themes, and produces a structured list of questions and answers that can be added to product or landing pages.

**Use Case**: Marketing and product teams can quickly generate FAQs that improve website engagement, answer customer questions proactively, and increase organic traffic.

**Key Features:**
- Automated Content Scraping: Pulls text directly from any product or homepage.
- Smart FAQ Generation: Produces relevant, clear, and accurate Q&A pairs aligned with the page content.
- One-Click Workflow: Runs instantly via the browser extension, no manual formatting needed.
- SEO Benefits: Adds fresh, structured content that improves discoverability and user experience.
- Ready-to-publish format

[🔗 Try it out](https://app.mindstudio.ai/agents/faq-generator-for-homepage-3b25f773/remix)

[🔗 Demo Recording](https://youtu.be/YUhEEGp5XBs)

---
### Slack Channel Weekly Summary  
**Description**: The Slack Channel Weekly Summary Agent automatically generates weekly activity reports from any Slack channel, ensuring teams stay aligned without sifting through long message histories.

**Use Case**: Team members can get comprehensive weekly summaries of important Slack channels that are meant for customer support queries, escalations, product bugs and outages without scrolling through hundreds of messages.

**Key Features:**
- Automated Schedule: Runs weekly (or on a custom cadence) with no manual triggering needed.
- Smart History Retrieval: Collects messages from the past seven days in the specified channel.
- AI-Powered Summaries: Analyzes conversations and compiles insights into a structured, digestible report.
- Custom Report Formatting: Uses Slack Block Kit JSON to format reports with clear sections (summary, active users, common questions, engagement highlights).
- Seamless Delivery: Posts the formatted report directly to a chosen Slack channel for team visibility.

[🔗 Try it out](https://app.mindstudio.ai/agents/slack-channel-weekly-summary-daa61017/remix)

[🔗 Demo Recording](https://youtu.be/ePgi_Zx22lY)

---
### YouTube Summarizer Agent  
**Description**: The YouTube Summarizer Agent streamlines video consumption by automatically generating concise takeaways from both the video transcript and its comments section. Triggered directly via a Chrome extension, the agent fetches the video transcript, applies AI summarization, and combines it with a sentiment-driven analysis of the top viewer comments.

**Use Case**: This agent accelerates market research, trend monitoring, and competitive intelligence by turning unstructured video + comment data into immediately usable insights. Teams save hours otherwise spent watching videos and parsing noisy comment threads—helping businesses stay ahead with faster, more informed decisions.

**Key Features:**
- Transcript Summarization: Condenses lengthy YouTube videos into clear, actionable summaries.
- Comment Analysis: Extracts themes, opinions, and feedback from the comments section.
- One-Click Workflow: Activated directly from the browser, no extra steps needed.
- Combined Output: Presents both video and comment insights together for a holistic view.

[🔗 Try it out](https://app.mindstudio.ai/agents/youtube-summarizer-agent-027a8d58/remix)

[🔗 Demo Recording](https://youtu.be/vFy1tihs_ng)

---

### Dynamic Content Generator  
**Description**: Creates custom content (tweet storms, LinkedIn posts, or blog posts) in specified tones using webpage content as context.

**Use Case**: Content marketers can instantly transform any article or webpage into engaging social media content across multiple platforms.

**Key Features:**
- Multi-format content creation
- Tone customization
- Context-aware generation
- Cross-platform optimization

[🔗 Try it out](https://app.mindstudio.ai/agents/dynamic-content-generator-ae1f77d6/remix)

---

### BlogPost Generator  
**Description**: Collects user-defined topics via a form and generates well-structured blog posts using AI.

**Use Case**: Content creators can quickly produce high-quality blog posts on any topic without spending hours on research and writing.

**Key Features:**
- Topic-based generation
- Structured formatting
- AI-powered writing
- Form-based input system

[🔗 Try it out](https://app.mindstudio.ai/agents/blogpost-generator-ae361fbb/remix)

---

### LinkedIn Post Generator  
**Description**: The LinkedIn Post Generator Agent transforms any article or webpage into a ready-to-publish LinkedIn post with built-in human review. Triggered via the Chrome extension, it extracts the page content, generates an engaging post, and appends the original link for context and credibility.

**Use Case**: This agent allows busy professionals and marketing teams to keep a consistent, high-quality presence on LinkedIn without spending hours crafting posts. It blends automation with human control, making content creation faster, while still maintaining the brand’s voice and authenticity.

**Key Features:**
- One-Click Post Creation: Scrapes webpage or article content to generate a professional LinkedIn post.
- Automatic Link Embedding: Ensures the source URL is included for transparency and reach.
- Human-in-the-Loop Editing: Checkpoint system allows users to review, revise, or reject drafts before publishing.
- Direct Publishing: Once approved, posts are sent straight to LinkedIn with hashtags and formatting in place.

[🔗 Try it out](https://app.mindstudio.ai/agents/linkedin-post-generator-6cc60c1b/remix)

---

### Email Summarizer  
**Description**: Processes forwarded email threads, condenses them into key takeaways, and sends results back as email notifications.

**Use Case**: Executives can quickly understand lengthy email chains by forwarding them to the agent and receiving concise summaries.

**Key Features:**
- Email thread processing
- Key takeaway extraction
- Automated summarization
- Email notification system

[🔗 Try it out](https://app.mindstudio.ai/agents/email-summarizer-e9440c21/remix)

---

### Email Thread Summary and Reply Agent  
**Description**: The Email Response Agent streamlines workplace communication by automatically generating professional email drafts. By forwarding any incoming email to the agent’s trigger address, it analyzes the content, drafts a clear and appropriate reply, and returns the draft to your inbox—ready to copy, paste, and send.

**Use Case**: Ideal for professionals handling large volumes of communication, this agent reduces time spent on repetitive drafting while ensuring tone consistency. It enhances productivity by letting teams focus on decision-making and relationship-building rather than email formatting.

**Key Features:**
- Email Triggered: Activated by simply forwarding an email to a dedicated address.
- Context-Aware Drafts: Analyzes the original email and crafts tailored responses that address all points, questions, or requests.
- Tone & Style Controls: Maintains professionalism with clarity, courtesy, neutrality, and confidence without harshness.
- Breakdown & Transparency: Provides a short rationale for why the draft was structured the way it was, giving users visibility into the AI’s choices.
- Seamless Output: Sends the draft and breakdown back via email, ready for quick review and reply.

[🔗 Try it out](https://app.mindstudio.ai/agents/email-thread-summary-and-reply-agent-3e1ffe7d/remix)

---

### Extract and Save People Information from Webpage in Sheets  
**Description**: This agent automatically extracts structured information about people mentioned on any webpage and stores it in a connected Google Sheet database. It’s a powerful tool for researchers, recruiters, and business development teams who need to capture leads and build contact lists quickly.

**Use Case**: Sales & Lead Generation – Building prospect lists from event pages, press releases, or company websites; Recruiting & Talent Sourcing – Extracting speaker bios, professional profiles, or team pages into structured formats; Market Research – Rapidly compiling datasets of industry players from public sources.

**Key Features:**
- Browser Extension Trigger: Runs directly on the webpage you’re viewing for seamless capture.
- Structured Data Extraction: Identifies people’s names, occupations, company names, notes, and profile image URLs from the raw HTML of the page.
- Google Sheets Integration: Automatically appends extracted data into a pre-defined Google Sheet, ensuring a single, consistent database is maintained.
- Image Handling: Captures and saves profile picture URLs when available.
- Confirmation Output: Displays a clean markdown table of the extracted people for instant review after each run.

[🔗 Try it out](https://app.mindstudio.ai/agents/extract-and-save-people-information-from-webpage-in-sheets-95669440/remix)

---

### Personalized Cold Outreach Generator  
**Description**: This agent automates the creation of tailored cold outreach emails for new leads. Built inside Mind Studio, it leverages company background data and specific lead information to generate personalized pain points and craft compelling email copy.

**Use Case**: This agent allows sales and marketing teams to scale cold outreach without losing personalization. It reduces the time spent researching prospects, ensures messaging consistency, and improves the likelihood of engagement by addressing real pain points. In practice, it transforms lead data into sales-ready emails at speed.

**Key Features:**
- Trained Contextual Knowledge: Uses system prompts loaded with company info to ensure all outreach aligns with brand positioning.
- Lead-Specific Personalization: Accepts lead details (uploaded file, CRM, or form entry) and extracts company attributes, values, and challenges.
- Pain Point Discovery: Identifies key problems the lead may face that the company’s product/service can solve.
- Email Generation: Produces structured cold emails (subject + body) personalized to each lead, ready for sales teams to deploy.

[🔗 Try it out](https://app.mindstudio.ai/agents/personalized-cold-outreach-generator-62f336db/remix)

---

### TL;DR Read a Webpage in Seconds  
**Description**: A browser extension that extracts and summarizes key points from any webpage, YouTube transcript, or PDF.

**Use Case**: Students and professionals can quickly digest lengthy articles, research papers, or documentation by getting instant summaries of the most important points.

**Key Features:**
- Multi-format support (web, video, PDF)
- Instant summarization
- Browser extension convenience
- Key point extraction

[🔗 Try it out](https://app.mindstudio.ai/agents/tldr-read-a-webpage-in-seconds-9cd8d6e3/remix)

---

## 📬 Contact Me

Ready to streamline your workflows with custom AI solutions? I specialize in building intelligent agents that solve real business problems and boost productivity.

**I can help you with:**
- **Custom AI agent development**
- **Workflow automation solutions**
- **Content generation systems**
- **Data analysis and monitoring tools**

Let's discuss how AI can transform your business processes and save you valuable time.

[📧 Get in touch](mailto:survemrunal94@gmail.com.com) or [💼 Connect with me on LinkedIn](https://www.linkedin.com/in/mrunal-surve-iimi/) to explore custom AI solutions for your needs!

```
