🤖 AI can write my LinkedIn posts, but I still want the final say. So I built a human-in-the-loop agent!

Fully automated posting is risky. One bad AI post can hurt your reputation. So I built a workflow with an approval step using n8n.

How it works:

📝 Form trigger: I submit a topic.

🧠 AI Agent: powered by Google Gemini and Tavily web search, it researches the topic and drafts the post.

📧 Approval by email: the draft lands in my inbox, and the workflow pauses until I reply.

🏷️ Text Classifier: AI reads my reply and decides whether it means approved or declined.

✅ Approved: the post goes live on LinkedIn automatically.

🔁 Declined: a Revision Agent rewrites the post using my feedback and sends it back for review. This repeats until I’m happy.

What I learned:

- Pausing workflows and waiting for human input
- Using AI to classify free-text replies instead of rigid buttons
- Building feedback loops with multiple agents

The best AI automation doesn’t replace humans. It makes them faster while keeping them in control. 🙌