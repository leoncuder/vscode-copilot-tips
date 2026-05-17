# Developer Prompt Tips

This summary covers four effective prompt strategies for developers, based on the transcript.

## 1. Q&A Strategy Prompt
- Ask the AI to ask you questions so it can refine its own prompt.
- Provide your project context, then answer a series of yes/no or short questions.
- Use short, direct responses and keep the flow moving even if later questions require more detail.
- Benefit: the AI helps you add details you might have missed initially, so you don’t need a perfect prompt from the start.

## 2. Pros and Cons Prompt
- Ask the model for multiple implementation options and the pros and cons of each.
- Include the specific file or code you want reviewed.
- Example use case: compare patterns for database connection logic.
- Benefit: you get several practical alternatives and can choose the best fit for your app.

## 3. Stepwise Chain of Thought Prompt
- Ask the AI to break a task into steps and perform one step at a time.
- Use a magic keyword like `next` to instruct the model to wait before continuing.
- Validate each step before moving on, especially during large refactors.
- Benefit: reduces risk by making changes incremental and reviewable.

## 4. Role Prompt
- Tell the AI to play a specific role (teacher, coach, expert, etc.).
- Define what the role is good at and how you want to learn or work.
- Combine this with stepwise guidance and ask the model to nudge you rather than just giving answers.
- Benefit: makes the AI behave more consistently and adapt to your workflow or learning style.

## General Guidance
- Use these strategies to work smarter, not harder.
- Be explicit about the goal and the format you want.
- Keep prompts iterative and interactive rather than trying to write the perfect prompt on the first try.
- Leverage the AI’s ability to ask questions, compare alternatives, proceed step-by-step, and adopt useful roles.
