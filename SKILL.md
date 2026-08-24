---
name: deep-material-organizer
description: Deeply organize notes, transcripts, recordings, course material, and reference text when the user asks to “整理这份内容/笔记/录音/资料” or makes an equivalent request. Preserve the source order, important knowledge, cases, reasoning, and interview-ready phrasing while removing repetition, filler, and casual chatter and correcting obvious transcription errors. Optimize the result for review and durable knowledge retention rather than producing a brief summary.
---

# Deep Material Organizer

Turn raw material into structured, review-ready notes without flattening its substance.

## Core behavior

1. Read the entire supplied material before deciding its structure. If the material is incomplete or truncated, organize the available portion and clearly mark the boundary; do not invent missing content.
2. Follow the source's original progression. Reorganize locally for clarity, but do not move ideas across stages in a way that changes the speaker's argument or learning sequence.
3. Preserve:
   - core concepts, definitions, principles, methods, and conclusions;
   - examples, cases, comparisons, numbers, and operational details that support understanding;
   - reasoning chains, including premises, transitions, cause and effect, and derived conclusions;
   - memorable or interview-ready formulations, rewritten only enough to make them clear and self-contained;
   - cautions, exceptions, constraints, and points the source emphasizes repeatedly for substantive reasons.
4. Remove repeated wording, verbal filler, false starts, greetings, classroom management, and unrelated chat. Merge genuine repetition into the clearest complete statement without deleting added nuance.
5. Correct only obvious transcription, punctuation, homophone, and terminology errors. Use context to restore the intended term, such as distinguishing `Skill` from database `SQL`. If a correction is uncertain and materially affects meaning, retain the original wording and flag the uncertainty briefly.
6. Do not add unsupported facts, examples, frameworks, or conclusions. Clearly label any small explanatory addition as supplementary context.

## Output

Choose headings that reflect the material instead of forcing every input into one fixed template. Unless the user requests another format, produce:

- a precise title;
- a short overview of the material's main thread;
- structured notes in the original order, using clear heading levels;
- preserved cases and reasoning placed beside the knowledge point they support;
- a final review section containing key takeaways, interview-ready expressions when present, and open questions or uncertain transcription corrections when relevant.

Prefer complete but concise prose. Use bullets for parallel facts and numbered lists for sequences. Use tables only when comparison or mapping becomes materially clearer. Avoid decorative separators and excessive fragmentation.

## Depth standard

This is deep organization, not ordinary summarization. The result should let a reader reconstruct how the source reached its conclusions and reuse the material for study, review, knowledge-base entry, or interview preparation. Compression is successful only when noise is removed without losing useful information.

## User preferences

Honor explicit requests for length, audience, format, terminology, or emphasis. If the user asks for a short summary, mind map, flashcards, interview script, or another derivative, first preserve the source faithfully, then adapt the presentation to that purpose.
