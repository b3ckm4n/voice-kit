# Voice Kit

**Use AI to become a better writer without outsourcing the thinking that makes writing valuable.**

Voice Kit is a model-independent writing workflow built around **generative friction**: AI creates the conditions for the writer to produce more substance, understand it more deeply, and express it in their own voice.

It began with a simple failure mode:

> The document can get better while the writer doesn't.

A polished draft can arrive before the writer has developed the ideas, judgment, or ownership needed to finish it. Voice Kit slows the process down in useful places. Early modes ask questions and expose gaps. Later modes help the writer structure, compose, and revise their work.

**Author-first drafting is the default.** The writer writes or dictates manuscript prose. AI offers questions, structural advice, diagnosis, and explanations of editing choices. Model-written passages are available only when the writer explicitly requests them; entering a mode or approving an outline is not permission to compose.

## Start here

1. Copy [the voice profile template](templates/voice-profile.md) and fill in what you know. Leave the rest blank.
2. Choose the mode that matches the maturity of your ideas.
3. Give your AI the shared rules in [VOICE-KIT.md](VOICE-KIT.md), the selected mode, your profile, and your source material.
4. Stay in that mode until its exit test is true. Move forward deliberately; move backward whenever the writing exposes a gap in your thinking.
5. Afterward, use the [session note](templates/session-note.md) to capture what the interaction helped you discover.

You do not need a particular model, app, or editor. The kit is a set of Markdown instructions designed to travel with you.

## The five modes

| Mode | Use it when | AI's job | Writer's job |
|---|---|---|---|
| [Think](modes/think.md) | The idea is still forming | Ask questions that elicit substance | Explore, react, dictate, and discover |
| [Architect](modes/architect.md) | The substance exists but the shape does not | Propose relationships, sequence, and medium | Judge the argument and identify what is missing |
| [Draft](modes/draft.md) | The ideas and structure are mature enough to express | Help the writer compose; supply prose only on explicit request | Write or dictate the draft and work through writing choices |
| [Edit](modes/edit.md) | The draft says what the writer means | Diagnose clarity, pace, and precision; supply replacements only on explicit request | Revise and choose what to adopt |
| [Rewrite](modes/rewrite.md) | The writer explicitly wants a new expression of mature material | Generate a bounded alternative | Compare it against the intended meaning and voice |

This is not a rigid pipeline. If an edit exposes a missing idea, return to Think. If the architecture requires substance that does not exist, stop and ask for it.

## The authorship test

Before calling a piece finished, the writer should be able to:

- explain the central idea without reading the document;
- defend the important claims and choices;
- identify what changed in their thinking;
- recognize the language and judgment as their own; and
- name where AI proposed something substantive that they chose to adopt.

Authorship is not a count of keystrokes. A writer can dictate every word and still own the thinking. They can also type an argument supplied by AI and contribute very little intellectually.

Intellectual ownership, recognition of one's voice, and practice composing prose are separate outcomes. Record who composed the passages and what writing choices the writer practiced. Passing the authorship checks does not by itself demonstrate improvement in independent composition.

## What Voice Kit is testing

Voice Kit is an early open-source experiment, not a proven writing method. Its working hypothesis is:

> A developmental-editor workflow built around questions, dictation, and reflection will produce more original thought and stronger authorship than asking AI for a near-finished draft.

The workflow has helped the same writer publish two essays: [“How I Became a Meat Proxy”](https://qvia.ai/writing/how-i-became-a-meat-proxy/) and [“I Needed Five Me’s. We Needed a New Way to Work.”](https://qvia.ai/writing/i-needed-five-mes/). The [first experiment](examples/first-experiment.md) describes the initial change in workflow; the [second experiment](examples/second-experiment.md) records repeat use and the corrections it exposed.

These are two completed AI-assisted writing tasks by one writer. The writer initially reported voice fit and actively reviewed the work, then questioned how much of the expression came from the model and whether the process provided enough composition practice. In the second task, AI generated the first continuous draft and most prose revisions from the writer's material.

The essays do not demonstrate improvement in independent composition or validate the author-first default introduced in response to this limitation. Measured improvement in understanding, comparative effectiveness, and use by other writers remain open.

A subsequent [usage note](examples/process-note.md) records writing a public reflection on authorship. Working through disconnected excerpts stalled; the writer explicitly requested a connected draft from their dictation, then supplied further material and directed revisions. This informed the optional [draft-from-dictation workflow](modes/draft.md#draft-from-dictation-on-request). It adds an example of adapting the process for the same writer, without establishing improved writing skill.

## What useful feedback looks like

If you try the kit, the most useful evidence is not whether the prose sounded polished. It is whether:

- a question caused you to discover a meaningful new idea;
- you understood the subject better afterward;
- the final piece sounded like you;
- you could explain and defend it to another person; and
- the friction felt generative rather than administrative.

See [CONTRIBUTING.md](CONTRIBUTING.md) for ways to share evidence or improve the workflow.

## License

[MIT](LICENSE)
