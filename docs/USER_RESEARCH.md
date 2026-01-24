# Who We're Building This For

## High School & College Students with Dyslexia

We're designing for students who get it: intellectually. They can understand complex ideas about photosynthesis or historical analysis or calculus. But the moment they open a textbook or article, something shifts. The words don't flow. Sentences feel tangled. Reading that should take 20 minutes takes an hour, and by then their brain is exhausted.

These are sharp students dealing with unnecessary friction that has nothing to do with their intelligence.

---

## The Real Problems We're Solving

### Comprehension Isn't the Issue: Access Is
A student with dyslexia can absolutely understand Hamlet or the causes of World War II. What they can't do is easily annotate a dense paragraph written in unnecessarily complicated language. If we strip out the clutter and present the same idea clearly, suddenly they're fine. The problem was never the concept, it was the presentation.

### Reading Fatigue Is Real
Reading is exhausting for someone with dyslexia. Not because they're not smart enough, but because their brain is working overtime to decode words while also trying to understand meaning. By halfway through a textbook chapter, they're drained. They might give up, skim, or forget what they just read. A toolkit that simplifies text and adds visual structure? That changes everything.

### Nobody Organizes Information for Them
A typical textbook or article expects readers to do all the work: figure out what's important, find the connections, build the structure. Students with dyslexia need that structure handed to them, not because they can't think, but because they're already burning mental energy on reading. A mind map that shows "here's the main idea, here's how it connects to other ideas" is like turning on a light.

### This Isn't About Reading Faster
We're not trying to turn someone with dyslexia into a speed reader. That misses the point. This is about removing barriers so they can actually learn. When the words stop getting in the way, students can:
- Actually understand what they're reading
- Remember it longer
- Feel confident tackling hard material
- Focus on learning instead of decoding

---

## Who Else Benefits

Teachers who want to make their materials accessible to all students. Parents helping their kids with homework. Students with ADHD or other processing challenges who just need information presented more clearly. These tools work for them too.

---

## How You'll Know This Works

A student finishes reading an article and actually remembers it. They tackle a challenging chapter without total brain meltdown. They feel capable. They stop avoiding reading altogether. The tool disappears into the background because it just... works.

---


##  What We Are NOT Building

We're being intentional about scope. There are a lot of great tools out there doing specific things really well, and we're not trying to reinvent those wheels. Here's what's outside our lane:

**Text-to-speech engines**: Yes, audio is valuable for accessibility. But that's a whole different problem with its own challenges, decent TTS requires specialized infrastructure, licensing, and engineering. Tools like Natural Reader and Google's read-aloud already do this. We're focusing on the reading experience itself, not replacing it with audio.

**Writing assistants**: Many students with dyslexia struggle with writing too, and that matters. But writing support is its own beast;grammar checking, sentence restructuring, organization. That needs different models and different UX. We're staying focused on consuming information, not producing it.

**OCR (optical character recognition)**: If you have a printed book or handwritten notes, OCR turns them into digital text. Important tool, but it's not us. There are solid OCR solutions out there. Our toolkit works with text that's already digital.

*Why does this matter?* Because trying to do everything means doing nothing well. We're laser-focused on one thing: making complex written information accessible and easier to understand. That's hard enough.

---


## Success Metrics

We're not guessing whether this works. These are the concrete measurements we're tracking to know if we're actually helping.

**Text Simplification**

**Flesch-Kincaid Grade Level**

*Target*: Reduce from original grade level to 6th-8th grade reading level maximum

*Why it matters*: Students with dyslexia benefit from text pitched at accessible reading levels without dumbing down the content

*How we measure*: Run toolkit output against original text through standard readability formulas

**SARI Score (Simplicity, Adequacy, Redundancy)**

*Target*: SARI score of 40+ (validates simplification preserves meaning while reducing complexity)

*Why it matters*: We're not just making text shorter,we're making it clearer while keeping the actual concepts intact

**Meaning Preservation**

*Benchmark*: 90%+ semantic similarity between original and simplified text (measured via embeddings)

*Why it matters*: A simple sentence that changes the meaning is useless. We need simplification that doesn't lose the point.


**Concept Extraction**

**Human Agreement Rate**

*Target*: 80%+ overlap between toolkit-identified concepts and concepts identified by educators and students

*How we measure*: Have teachers and students read texts, mark key concepts. Compare their results to what our model extracts.

*Why it matters*: If our toolkit misses important ideas or flags irrelevant ones, it fails students

**Concept Hierarchy Accuracy**

*Target*: 75%+ correct parent-child relationships in concept hierarchies

Why it matters: It's not enough to identify concepts,they need to connect logically. A concept map that shows wrong relationships confuses rather than clarifies.

**Coverage**

*Target*: Identify 85%+ of main concepts a human expert would identify

*Why it matters*: Missing key ideas defeats the purpose



**User Testing Results**

*Target*: 80%+ of student users report improved comprehension and reduced fatigue when using simplified + concept-mapped content vs. original text

*Measurement*: Quick post-use survey: "Did you understand this better?" "Did it feel less exhausting?"

*Why it matters*: All the metrics in the world don't matter if students don't actually feel the difference


**User Impact (The Real Test)**:
Learning Outcome Improvement

*Target*: Students using the toolkit show measurable improvement on comprehension assessments (aim for +15-20% accuracy compared to reading original text alone)

*How we measure*: Pre/post assessments with student cohort

*Why it matters*: This is the whole point. Does it actually help learning?

**Engagement & Completion**

*Target*: Students complete 90%+ of assigned reading with the toolkit vs. 60-70% without it

*Why it matters*: If students avoid the material anyway, we've failed

---

## Chosen Initial Domain: High School Algebra & Geometry
Why math? Word problems and multi-step explanations are reading-heavy and confusing. Students understand the concept but get lost in the explanation. Geometry especially benefits from visual concept maps. High stakes, measurable progress.

**Competitive Landscape
What exists**:

*Text simplification*: Hemingway, Newsela but no dyslexia focus or concept mapping

*Accessibility*: Immersive Reader, Read&Write, good fonts/spacing, but don't simplify complex text

*Mind mapping*: XMind, MindMeister, great tools, but manual. No AI extraction.

*Math tools*: Khan Academy has excellent explanations but don't fix the textbook reading problem

*The gap*: Nobody combines AI text simplification + automatic concept extraction + dyslexia-friendly design in one tool.

**Why we win**: Integrated, automatic, dyslexia-first, open source. One tool. No friction.

---

## How We Compare

| Product | What They Do | What We Do Differently |
|---------|-------------|------------------------|
| Hemingway, Grammarly | Make writing clearer | Dyslexia-specific simplification + concept extraction + visual mapping |
| Immersive Reader, Read&Write | Accessibility features (fonts, spacing, audio) | Add AI text simplification so students understand, not just read comfortably |
| XMind, MindMeister | Manual concept map creation | Automatically extract and visualize concepts; no extra work |
| Newsela | Simplify news articles | Target academic textbooks and extract key concepts visually |
| Khan Academy, PhET | Video explanations & simulations | Simplify the textbook itself for independent learning |
| **Breakthrough Tech Dyslexia Toolkit** | **—** | **Integrated pipeline: simplify,  extract,  visualize, dyslexia-optimized** |