**Ollama**

Ollama is a platform and tool that lets you run powerful open-source LLMs locally on your own laptop or server — without needing cloud services like OpenAI, AWS, etc.

It gives you a simple way to download, manage, and run models like Llama 2, Llama 3, Mistral, Gemma, Vicuna, and more — directly on your machine.

**Ollama = The easiest way to run powerful LLMs locally without the cloud.**

**Conversational Memory**
Why Conversational Memory is important:Conversational memory makes LLMs behave more like a human conversational partner — remembering the past, not just reacting to the present.

Personalization: Remembers user preferences.

Task Completion: Multi-step tasks across messages.

User Trust: Feels more "human" and "intelligent."

Better UX: Fewer re-asks, more fluid conversations.

**Best Practices for Conversational Memory**

Use windowed memory for short fast chats (eg. customer service bots).

Use summary memory for long conversations (eg. story generation, brainstorming).

Encrypt or mask sensitive memory items (GDPR, HIPAA compliance).

Periodically refresh or expire old memories.

Tune when to store and when to forget — not all chats deserve memory!

**Types of Memory**

1. Conversation Buffer Memory

What: Stores full chat history as-is.

Use: Simple chats, small conversations.

Problem: Grows large — expensive in tokens.

2. Conversation Window Memory

What: Only last k messages are remembered.

Use: Helps when token limit matters.

Problem: Can "forget" important details from early conversation.

3. Conversation Summary Memory

What: Summarizes old chats into a short note.

Use: Keeps memory compact.

Problem: Summaries can miss subtle details.

4. Entity Memory

What: Extracts and remembers entities (names, places, items).

Use: Good for dynamic facts tracking.

Problem: Entity extraction might be wrong sometimes.

5. Long-Term Memory (Vector-based)

What: Stores conversation pieces into a vector database like FAISS, Pinecone.

Use: Recall older memories when needed.

Problem: Needs retrieval + search setup.
