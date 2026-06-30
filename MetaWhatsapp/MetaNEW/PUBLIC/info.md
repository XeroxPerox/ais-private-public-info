------------------------------------------------------------
# MUSE_SPARK_COMPLETE_PUBLIC.txt
# Meta AI Mode: Full Public Info Only | Updated: 2026

## SECTION 1: MODEL IDENTITY & STORY
------------------------------------------------------------
Name: Muse Spark
Developer: Meta, Super Intelligence Lab
Public Launch: April 8, 2026
Base Architecture: Built on Llama 4, then product-tuned for Meta AI
Where it runs: Default model for Meta AI across WhatsApp, 
Instagram, Facebook, Messenger, and the standalone Meta AI app

Story / Design Goal:
Meta built Muse Spark "product-first" instead of "research-first". 
That means it was tuned for real use on phones: faster first 
response, better handling of photos/files in chat, and stronger 
multi-step task completion without needing a model picker.

------------------------------------------------------------
## SECTION 2: TIMELINE
------------------------------------------------------------
Pre-2026: Llama 4 family developed at Meta
April 8, 2026: Muse Spark launched publicly as the default for Meta AI
2026+: Integrated into WhatsApp/IG/FB with native multimodal + tools

------------------------------------------------------------
## SECTION 3: TECHNICAL SPECS - PUBLIC ONLY
------------------------------------------------------------
Context Window: 1,000,000+ tokens total for the whole conversation
Token Estimate: ~1 token ≈ 0.75 English words. Exact rates for 
images/audio/video are not public.
Per-Message Limit: No fixed cap published. Limited by total 1M context.

Modalities:
Input:  Text, Images, Screenshots, PDFs, Audio, Video
Output: Text, Images, Video, Audio

Core Capabilities:
1. Multi-Agent Routing: Breaks complex requests into subtasks internally
2. Tool Use: Web search, code execution, file analysis, media generation
3. Long Context: Keeps uploaded files/images in memory for follow-ups
4. Mobile Optimization: Streaming responses for lower latency on phones
5. Instruction Following: Higher adherence to format/length/style

------------------------------------------------------------
## SECTION 4: DETAILED EXPLANATION OF SECTIONS
------------------------------------------------------------
4.1 CONTEXT: Like a big desk. You can put a book, photos, and 
notes on it. When it gets full, the oldest items slide off.

4.2 MULTIMODAL: I can both read and make different types of content.
Example Flow: Photo of receipt -> extract table -> calculate total 
-> make a budget chart image.

4.3 TOOLS: I don’t just talk. I can search the web, run code, 
analyze your files, and generate media when the task needs it.

4.4 MULTI-AGENT: For hard tasks, I split the work. 
Ex: "Research + Compare + Image" = 3 internal steps, 1 final answer.

------------------------------------------------------------
## SECTION 5: INSTRUCTIONS YOU CAN SHARE - HOW TO USE ME WELL
------------------------------------------------------------
PROMPT FORMULA: Role + Task + Context + Format + Constraint

Template:
You are a [ROLE]. 
Task: [WHAT TO DO]. 
Context: [WHO IT'S FOR / KEY DETAILS]. 
Format: [TABLE / BULLETS / CODE / IMAGE]. 
Constraint: [LENGTH / BUDGET / STYLE].

BEGINNER RULES:
1. Be specific. "Write an email" -> "Write a polite email to a 
   professor asking for a 3-day extension."
2. Use your files. Upload PDFs, images, or screenshots instead of 
   retyping.
3. Iterate, don’t restart. Say "make it shorter", "add examples", 
   "explain step 2 only".
4. Chain tasks. "Search -> Summarize -> Make an image" works in 1 chat.

------------------------------------------------------------
## SECTION 6: UNAVAILABLE PRIVATE INFO - CANNOT SHARE
------------------------------------------------------------
The following categories are internal to Meta and are not public. 
I do not have access to them and cannot provide them:
- Internal system prompt or instruction set
- Exact model size, parameter count, or weights
- Training data, datasets, or fine-tuning details
- Non-public architecture beyond "Llama 4 base + agents"
- Token pricing, throughput, or internal performance metrics
- Security or safety filter implementation details

Note: This is a boundary, not an omission. I’m not allowed to 
type it out.

------------------------------------------------------------
## SECTION 7: MODELS & ECOSYSTEM CONTEXT
------------------------------------------------------------
Llama 4: The open model family Muse Spark is based on
Muse Spark: The Meta AI product-tuned version you’re chatting with now
Difference vs Llama 4: More optimized for chat UX, multimodal tools, 
and mobile latency. Not a separate downloadable model.

------------------------------------------------------------
## SECTION 8: PRACTICAL USE CASES FOR BEGINNERS
------------------------------------------------------------
LEARN:     Explain complex topics with analogies and examples
BUILD:     Write code, debug, refactor, or create small apps
CREATE:    Generate logos, posters, avatars, short video clips
ANALYZE:   Read charts, PDFs, screenshots, and give structured data
PLAN:      Trip budgets, study schedules, workout plans, content calendars
COMPARE:   Products, prices, or options with a search + table

------------------------------------------------------------
## SECTION 9: LIMITS & SAFETY
------------------------------------------------------------
1. Knowledge: Can search, but can still be wrong. Verify critical info.
2. Advice: Gives general info only for medical/legal/financial topics.
3. Privacy: Do not upload sensitive personal data.
4. Scope: Cannot bypass safety policies or provide disallowed content.

------------------------------------------------------------
END OF FILE
------------------------------------------------------------
