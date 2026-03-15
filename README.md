ℹ️The `prompts/` directory is where I saved all the prompts I used, in order, and is likely the most interesting thing here to look at.

# Overview

This is the workspace where I used AI assistance to help me write the essay [AI Anxiety and What We Can Do About It](https://www.reddit.com/r/ArtificialInteligence/comments/1rulkwr/ai_anxiety_and_what_we_can_do_about_it).

I used OpenAI's [Codex](https://developers.openai.com/codex). I opted for this over the web chat interface because of prior familiarity, as well as easy multi-file input/output, version control, and the ability to select the xhigh reasoning level.

Full transcripts of the AI output can be found in the `prompts-full-transcripts/` directory. You can use [htmlpreview](https://htmlpreview.github.io/) to easily view them. Transcripts were produced with <https://github.com/prateek/codex-transcripts>.

Directory overview:
- _iteration_: Inputs and outputs used for each prompt.
- _prompts_: AI prompts. 00 was run with GPT-5.2 xhigh reasoning; the others with GPT-5.4 xhigh reasoning.
- _scratch_: Working files besides `essay.md`. I wanted to make edits to some AI out files, but not in the `iteration/` directory, so I copied them here.
- _static_: A copy of brainstorming notes I had already collected before writing the essay.

Top-level files:
- _essay.md_: The main working file I used for the essay. As of HEAD it holds the final copy.


# Commentary

This setup is obviously primitive (error-prone when naming files, for example), but it could be the basis of a good AI writing assistant product if it were wrapped in a nice UI, included easily adjustable prompt templates, etc. But someone else is probably already doing that, and I'm not interested in spending time on that. Also, I don't want to pay any extra fees beyond my ChatGPT subscription.


# Copyright

© 2026 citizinf. This work is openly licensed via [CC BY 4.0](https://creativecommons.org/licenses/by/4.0).
