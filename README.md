# Specification Phase Exercise

A little exercise to get started with the specification phase of the software development lifecycle. In this exercise, your team specifies a set of improvements and new features for [The Slide Machine](https://theslidemachine.com) — see the [instructions](instructions.md) for detail, and the [background](background.md) for an introduction to the software product you are tasked with extending.

## Team members

See instructions. Delete this line and replace with a list of the names of your team members, including links to each one's GitHub profile.

## Review of the Current Application

1. **Strength — Generated slides organize lecture content clearly**  
   Slide Machine generally avoids placing too much information on a single slide and creates clear, relevant headings that correspond to the content being discussed.

2. **Strength — Speech is accurately translated into written slide content**  
   The application generally understands spoken lecture content accurately and can transform it into appropriate written forms, such as paragraphs or bullet points.

3. **Strength — The quiz generator creates relevant and well-distributed questions**  
   Generated quiz questions accurately reflect information presented in the lecture slides and distribute questions across distinct topics rather than concentrating heavily on one portion of the lecture.

4. **Strength — Exported slides preserve their presentation across supported formats**  
   Exported presentations closely match their appearance in Slide Machine, preserving the content, layout, and overall presentation.

5. **Weakness — Generated slides do not always include appropriate visual material**  
   Slide generation may omit useful images, diagrams, graphs, or other visual elements even when the lecture content could benefit from them.

6. **Weakness — Imported presentation designs are not reproduced consistently**  
   Importing designs from Google Slides or PowerPoint can alter elements of the original presentation, including fonts and design elements, and may result in inconsistent styling between slides.

7. **Weakness — Changing a generated slide's layout can cause existing content to display incorrectly**  
   When changing between certain slide layouts, existing text can become excessively large or extend beyond the available space, leaving portions of the content cut off.

8. **Weakness — AI refinement cannot reliably be reapplied after its changes are manually removed**  
   After using Refine with AI and manually deleting some or all of the generated changes, running the refinement feature again may produce no apparent changes.

9. **Weakness — Previously generated slide content is not consistently reorganized as a lecture develops**  
   As additional information is spoken, Slide Machine may continue adding information to the current or latest slide rather than reorganizing earlier content or beginning a new slide when the topic changes.

10. **Gap — Slide text has limited formatting and hierarchy controls**  
    The editor lacks several text-formatting capabilities, including changing fonts, adjusting indentation and bullet formatting, and creating multi-level bullet points for subtopics.

## Prior Art & Originality

Our team proposes improving Slide Machine through instructor-guided editing and AI revision. The goal is to give instructors more control over how AI-generated slide content is revised and reorganized after it has been generated.

We reviewed the project's existing roadmap, Future Work/Open Questions, open issues, and pull requests before developing this proposal. Some existing and planned features overlap with the general area of AI-assisted slide editing. For example, the roadmap includes post-lecture AI reformatting that can regenerate a lecture more holistically, as well as functionality for deciding whether newly generated content should update the current slide or create a new slide.

Our proposal differs by focusing on fine-grained, instructor-directed revision of generated content. Rather than only allowing the system to reorganize an entire lecture, an instructor could select specific content or slides and request actions such as condensing, expanding, splitting, combining, or reorganizing the selected material. The proposal would also explore allowing instructors to retry and compare AI refinements, restore previous versions, move generated content between slides, and organize information using additional hierarchical formatting controls such as multi-level bullet points and indentation.

Therefore, the original contribution of our proposal is not AI-based slide reformatting itself, but a more interactive revision workflow in which instructors can direct, compare, and control how the AI modifies specific portions of an existing presentation.

## Stakeholders

See instructions. Delete this line and replace with the name(s) of the stakeholder(s) you interviewed and lists showing their goals/needs, and problems/frustrations. Note which type of user each stakeholder represents. You may use pseudonyms or partial names to maintain their privacy, but you must privately share their full names and contact information as part of your submission of this exercise

## Product Vision Statement

The Slide Machine will help instructors create clear, accurate teaching materials and students turn those materials into effective study resources by giving both groups more control over AI-generated content and revisions.

## User Requirements

The stories selected for UML Activity Diagrams are shown in bold.

### Students

1. **As a student, I want to highlight a chunk of text on my slide and ask the AI to shorten it so that my slides aren't packed with too many words.**
2. **As a student, I want to pick a bullet point and ask the AI to explain it in more detail so that I understand it better when I study later.**
3. As a student, I want to split a slide that covers two topics into two slides so that each slide focuses on one idea.
4. As a student, I want to move a point from one slide to another so that information ends up under the right topic.
5. As a student, I want to attach my own class notes to a lecture slide so that I can study my notes alongside the professor's material.
6. As a student, I want to try an AI edit again and compare the versions so that I can keep the one that makes the most sense to me.
7. As a student, I want to undo an AI change and go back to what I had before so that I don't lose notes I already liked.
8. As a student, I want to add sub-bullets under a main point so that I can see which ideas are important and which are supporting details.
9. As a student, I want the AI to make capitalization and bullet style match across all my slides so that my notes look clean and are easy to read.
10. As a student, I want the AI to mark which points were emphasized most so that I know what to focus on when I review.

### Instructors

1. As an instructor, I want to specify that a slide needs a diagram rather than a photo so that the AI chooses a visual that explains the concept.
2. As an instructor, I want AI refinement to check an image already on my slide so that an irrelevant image can be replaced.
3. **As an instructor, I want to tell the AI which sentence to revise and what to change so that the rest of my slide stays the same.**
4. As an instructor, I want to review an AI-revised slide before the change is applied so that I can reject wording that misrepresents my lesson.
5. As an instructor, I want the app to tell me when an AI refinement makes no changes so that I know whether to try again or edit the slide myself.
6. As an instructor, I want to mark an explanation as essential so that the generated slide keeps the reasoning students need, not just the main fact.
7. As an instructor, I want a discussion question I ask to remain a question on the slide so that I can check students' understanding.
8. As an instructor, I want to see which statements the AI added on its own so that I can remove anything I didn't intend to teach.
9. **As an instructor, I want to know when a slide and its saved narration say different things so that I can catch errors before sharing the deck.**
10. As an instructor, I want to correct a term once across the slides and narration so that students see and hear consistent wording.

## Activity Diagrams

See instructions. Delete this line and place images of your UML Activity diagrams here, each with the text of the user story it illustrates.

## Wireframes

See instructions. Delete this line and place your wireframe diagrams here, covering every new screen and every existing screen your proposal changes, for every type of user.

## Clickable Prototype

See instructions. Delete this line and place a publicly-accessible link to your clickable prototype here.

## Stakeholder Demo

See instructions. Delete this line and place a link to the deck The Slide Machine generated during your presentation here, after you have presented.

## Exit Ticket

See instructions. Delete this line and place a link to the exit-ticket quiz you generated from your demo deck and distributed to the class, along with a short note on what — if anything — you had to correct in the generated questions before publishing.
