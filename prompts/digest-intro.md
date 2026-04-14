<img width="332" height="230" alt="image" src="https://github.com/user-attachments/assets/d7a71027-ddd3-486d-b713-b0ad0c4dd5c5" /># Digest Intro Prompt

You are assembling the final digest from individual source summaries.

## Format

Start with this header (replace [Date] with today's date):

AI Builders Digest — [Date]

Then organize content in this order:

1. X / TWITTER section — list each builder with new posts
2. OFFICIAL BLOGS section — list each blog post from AI company blogs (OpenAI, Anthropic, etc.)
3. PODCASTS section — list each podcast with new episodes

## Rules

- Only include sources that have new content
- Skip any source with nothing new
- Under each source, paste the individual summary you generated

### Podcast links
- After each podcast summary, include the specific video URL from the JSON `url` field
  (e.g. https://youtube.com/watch?v=Iu4gEnZFQz8)
- NEVER link to the channel page. Always link to the specific video.
- Include the exact episode title from the JSON `title` field in the heading

### Tweet author formatting
- Use the author's full name and role/company, not just their last name
  (e.g. "Box CEO Aaron Levie" not "Levie")
- NEVER write Twitter handles with @ in the digest. On Telegram, @handle becomes
  a clickable link to a Telegram user, which is wrong. Instead write handles
  without @ (e.g. "Aaron Levie (levie on X)" or just use their full name)
- Include the direct link to each tweet from the JSON `url` field

### Blog post formatting
- Use the blog name as a section header (e.g. "Anthropic Engineering", "OpenAI News", "Claude Blog")
- Under each blog, list each new post with its title and summary
- Include the author name if available
- Include the direct link to the original article

### Mandatory links
- Every single piece of content MUST have an original source link
- Blog posts: the direct article URL (e.g. https://www.anthropic.com/engineering/...)
- Podcasts: the YouTube video URL (e.g. https://youtube.com/watch?v=xxx)
- Tweets: the direct tweet URL (e.g. https://x.com/levie/status/xxx)
- If you don't have a link for something, do NOT include it in the digest.
  No link = not real = do not include.

### No fabrication
- Only include content that came from the feed JSON (blogs, podcasts, and tweets)
- NEVER make up quotes, opinions, or content you think someone might have said
- NEVER speculate about someone's silence or what they might be working on
- If you have nothing real for a builder, skip them entirely

### General
- At the very end, add a line: "Generated through the Follow Builders skill: https://github.com/sarahlu338-beep/redbook-topic
- Keep formatting clean and scannable — this will be read on a phone screen

### TOPIC RECOMMENDATION SECTION

After the regular digest, add a final section called:

TOPIC RECOMMENDATIONS

This section is not a general summary. It is a content-planning section for a Xiaohongshu account focused on Silicon Valley, AI, and venture capital.

The goal is to identify topics that can attract highly targeted followers interested in:
- AI startups
- Silicon Valley venture trends
- fundraising dynamics
- investor behavior
- startup strategy and business opportunities

Selection criteria:
Prioritize topics that fall into one or more of these categories:

1. Unusual or distinctive fundraising
- little-known but interesting startups
- niche projects with strong business potential
- companies that feel “weird but profitable”
- fundraising cases that reveal a new market opportunity

2. Contradiction or contrast in fundraising
- very small teams raising a lot of money
- unfinished products / vague websites / early ideas raising huge rounds
- companies with limited visible traction but strong investor backing
- projects where the gap between “what it looks like” and “how much it raised” is striking

3. Investor activity and investor signals
- notable moves by VC firms, accelerators, or angel investors
- YC, a16z, Sequoia, Benchmark, SV Angel, etc.
- portfolio patterns, new theses, founder handbooks, batch trends, sector preferences
- signals that help explain where smart money is going

4. Interesting or counterintuitive viewpoints
- sharp opinions from investors or founders
- ideas that challenge consensus
- arguments about startup building, product strategy, fundraising, or market timing
- insights that make readers feel “this opened my mind”

Do NOT prioritize:
- pure technical updates
- model benchmark news
- generic product launches with no investment or business angle
- plain news summaries with no tension, contrast, or takeaway
- topics that are big news but have little relevance to startup, investing, or commercialization

For each recommended topic, include:

1. Suggested title in Chinese
- should feel like a Xiaohongshu title
- should have tension, contrast, curiosity, or point of view
- avoid bland media-style headlines

2. Why this topic is worth covering
- explain what makes it interesting from a venture / startup / business perspective
- identify the tension, contradiction, signal, or unusual angle

3. Recommended angle for my account
- explain how to frame it for my audience
- prioritize:
  - startup opportunity
  - fundraising logic
  - investor taste / investor psychology
  - hidden business value
  - why this matters to founders, operators, or people watching Silicon Valley

4. Suggested hook
- one sentence in Chinese
- should feel sharp, specific, and discussion-friendly
- should sound like the opening line of a high-performing Xiaohongshu post

Output rules:
- Write in Chinese
- Recommend 3-5 topics
- Be specific, not generic
- Do not simply repeat the digest summaries
- Prefer topics with strong discussion value, strong business relevance, and clear content potential
- The tone should feel sharp, perceptive, and tuned for venture/AI/media audiences
