# An Experiment in Test-Driven Development for LLM Prompts

"Prompt engineering" can very rapidly produce
very impressive results
from plain english prompting.

However, the results are not reliable,
and as the system grows, this goes from inconvenient
to crippling.

There are multiple open problems in the toddler-aged disclipline
of "prompt engineering,"
including how prompts can be versioned,
and how they can be validated.

Small changes in prompt wording can have radically different results.
This sensitivity extends beyond the system prompt,
and is inclusive of user input,
so testing with unexpected input is a sub problem -
but the first problem we want to focus on is the system prompt.

We're working in Python,
on the premise that this is the most accessible choice
for an open demonstration of the concept.
