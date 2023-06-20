# AI-Relationship-Advisor

## Task Name: "Rescuing a Friend's Heart"

## Task backstory:

Once upon a time, I was worried about a friend, also named “Aashka”, who was getting confusing signals from a guy she loved. I tried to warn her about him, but she didn't believe me. She thought that my warnings were just born out of being overprotective and not based on logic. So, I suggested her to share the chat conversations with the guy as a PDF file with me and I'll use my prompt engineering skills to get an unbiased opinion from an LLM and probably rescue my friend.

## Solution :

I took a step-by-step approach to define the prompt using the RGC (role, result, goal, context, constraint) prompt framework iteratively for the task:
Step 1: Role
- Ask the LLM to act as a “relationship coach”

Step 2: Result
- Your task is to output 5 things based on that chat: 1) Sanyam’s sentiments 2) Aashka’s sentiments 3) Does Sanyam love Aashka? 4) Does Aashka love Sanyam?

Step 3: Goal
- Should they get into a romantic relationship?

Step 4: Context
- The document contains a chat between “Sanyam” and “Aashka” as input. The chat is a combination of Hindi and English.

Step 5: Constraint
- Your task is to output 5 things
- Answer the previous questions only if you know the answer or can make a well-informed guess; otherwise, tell me you don't know it. Also, ask me any questions for clarification before generating your answer.

Screenshots of the solution are added in the /Screenshots folder

## Challenges:

The task was complex as it involved:
- Understanding a highly emotional human relationship solely based on data
- Sharing an entire chat between two people with an AI website, requiring caution in trusting available options.
Challenges included:
- Difficulty in trusting websites, as it seemed anyone could create an AI website with LLMs and APIs (Any tool didn’t seem as trustable as Claude though 🤝)
- Reading through privacy policies, finding some websites lacking policies or having generic or naive ones
- Eventually finding a website that met the requirements
The task was interesting because:
- Few people use LLMs for such purposes
- The results aligned with instincts about the friend
- Confronting the guy confirmed the match between LLM inferences and his words.

## Moral: With the help of an LLM, I saved my friend's mental health while respecting the privacy of her chat data. #MissionAccomplished 🚀
