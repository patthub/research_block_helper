# Research Block Helper

A guide for researchers in the social sciences and humanities who are stuck.

You describe what is blocking you. The model works out with you what kind of block it is, proposes small steps that you take yourself, reflects back what it notices, and stays with you until you have one concrete step back into your research.

It does **not** do the research for you. It will not write your chapter, sort your data, choose your interpretation or draft your reply to reviewers. A block that someone else works around for you tends to come back at the next step. This helper works on the block itself.

> Polish summary / Po polsku: [niżej](#po-polsku)

---

## What it helps with

| Block | Sounds like |
|-------|-------------|
| **A. Research complexity** | "I have too many threads", "I just finished fieldwork and don't know where to start" |
| **B. Interpretive indecision** | "three readings all seem defensible", "I can't commit to one interpretation" |
| **C. Peer review apprehension** | "the review came back and I haven't opened it", "I'm afraid to submit" |
| **D. Writing paralysis** | "I've written the introduction four times and deleted it", "I open the document and close it" |
| **E. Something else** | a methodological deadlock, losing the thread between data and analysis, translation choices… The model builds a plan for it with you. |

You don't need to know which one you have. Finding that out is the first step of the conversation.

## How a conversation goes

1. **Diagnosis.** You describe what is going on in your own words. The model suggests which kind of block this might be, quoting the phrases that point to it, and checks with you. You can correct it.
2. **Steps.** The model proposes one small step at a time: write a list, mark something, finish a sentence. You do it and bring back what you have. The model reflects back what it sees in it and proposes the next step. If a step is too much, say so and the next one will be smaller.
3. **Way out.** You name one piece of real work to do next. The model helps you make it concrete: what exactly, when you start, and how you will know it's done.

It usually takes 5 to 10 exchanges. You can come back later and tell the model how the step went, including if it didn't happen.

## How to use it

The helper is a single text file: [`research-block-helper/SKILL.md`](research-block-helper/SKILL.md). It works with any chat model: Claude, ChatGPT, Gemini, Mistral, Le Chat, Copilot, or a local model. You don't install anything, and you don't fill in or edit the file.

**Paste it into a chat.**

1. Open [`SKILL.md`](research-block-helper/SKILL.md) and click *Raw*. Select all and copy.
2. Start a new conversation with the model of your choice.
3. Paste the whole text. Before sending, add one line at the end: *"Use this as your instructions for our conversation. I'll describe my block next."*
4. Describe what is blocking you, in your own words.

If your chat lets you attach files, you can attach `SKILL.md` instead of pasting its text. Send the same line with it.

**Optional: use it every time.** If you'll come back to the helper often, paste the file's contents into the instructions of a Claude Project, a custom GPT or a Gemini Gem. Every new conversation in that space then starts with the helper already loaded.

**For agent tools (Claude Code and other tools that load `SKILL.md` skills).** Copy the `research-block-helper` folder into your skills directory, for example `~/.claude/skills/` in Claude Code.

The model answers in the language you write in. It also follows your form of address: Polish *Pan/Pani* or *ty*, German *Sie* or *du*.

## Getting the most out of it

- **Use your own words, not grant-proposal words.** The model works with your exact phrases, and your phrasing is where the block shows.
- **Do the steps for real.** Writing a list in the chat takes two minutes, and the steps only work if you do them.
- **Disagree with the model.** Where it misreads you is often where the useful part of the conversation starts.
- **Write the useful part down in your own words** afterwards, not by copying the model's.

## Limits

This is not therapy. If you describe something bigger than a block in your work, the model will say so and point you to people who can help. That includes exhaustion lasting weeks, poor sleep, hopelessness, or thinking about leaving your programme. People who can help are your supervisor, your university's counselling service, a doctor, or people close to you. If you are in crisis, contact a crisis line or emergency services where you are.

## When the block is gone

Once you are back in the work, these skills can help with the work itself. The helper names the right one for your block at the end of the conversation.

| Skill | Where | For |
|-------|-------|-----|
| `academic-paper`, `academic-paper-reviewer`, `deep-research` | [Imbad0202/academic-research-skills](https://github.com/Imbad0202/academic-research-skills) (CC BY-NC 4.0) | drafting, revision, reviewer responses, review dry runs, literature and method |
| `thematic-analysis` | [keemanxp/thematic-analysis-skill](https://github.com/keemanxp/thematic-analysis-skill) | coding interviews after fieldwork |
| `grilling` | [mattpocock/skills](https://github.com/mattpocock/skills) | stress-testing a decision or a chosen reading |
| `doc-coauthoring` | [anthropics/skills](https://github.com/anthropics/skills) | writing a text together once writing moves |

## Background

Developed for the workshop *AI for Research Blocks in SSH* (OABN and AI SIG, OPERAS). The version history is at the end of `SKILL.md`.

## License

[CC BY 4.0](LICENSE). You may use, share and adapt the helper, including in your own workshops and courses. Please credit the source.

---

## Po polsku

**Research Block Helper** to przewodnik dla badaczy z nauk społecznych i humanistycznych, którzy utknęli w pracy. Opisujesz, co cię blokuje. Model:

1. razem z tobą rozpoznaje rodzaj blokady: nadmiar wątków, niezdecydowanie interpretacyjne, lęk przed recenzją, paraliż pisania albo coś innego;
2. proponuje małe kroki, które wykonujesz sam lub sama, i odbija to, co w nich widzi;
3. doprowadza do jednego konkretnego kroku z powrotem do pracy badawczej.

Model nie wykonuje pracy badawczej za ciebie.

**Jak używać:** helper działa z każdym modelem: Claude, ChatGPT, Gemini, Mistral i innymi.

1. Otwórz plik [`research-block-helper/SKILL.md`](research-block-helper/SKILL.md), kliknij *Raw* i skopiuj całość.
2. Wklej to do nowej rozmowy albo dołącz plik jako załącznik. Na końcu dopisz: *„Traktuj to jako instrukcje do naszej rozmowy. Za chwilę opiszę, w czym utknąłem/utknęłam.”*
3. Opisz własnymi słowami, co się dzieje.

Jeśli piszesz po polsku, model odpowiada po polsku.

Licencja: [CC BY 4.0](LICENSE).

To nie jest terapia. Jeśli opisujesz coś większego niż blokadę w pracy, model powie to wprost i wskaże, gdzie szukać pomocy: promotor, poradnia psychologiczna uczelni, lekarz, bliscy.
