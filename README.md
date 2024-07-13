# An Experiment in Test-Driven Development for LLM Prompts

You can collaborate with us on the developing the code
that forms the basis for work in this repo
by accessing our [Google Colab notebook][colab-notebook].

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

## Next Steps/Backlog

- [x] Setup initial notebook
- [x] Get one assertion passing using OpenAI's API.
- [x] Get repo pushed
- [x] Write next-steps list
- [ ] Test reliability of "you are echo say argh"
- [ ] Test more complex echo service examples
- [ ] Test reliability of more complex examples
- [ ] Maybe: TDD structured-data/function call for geoboxes
- [ ] Maybe: Make test use any one additional remote model
- [ ] Maybe: Make test use any one additional local model
- [ ] Maybe: Write CI representing repeat-run capability
- [ ] ...

[colab-notebook]: https://colab.research.google.com/drive/1Irt3jJs1Ft9WKXSfpg0CanOG9daolqBQ?usp=share_link
