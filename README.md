# Exno.7-Prompt-Engineering
# Date:21.5.25
# Register no.212222040091
# Aim: 

To Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Algorithm:

Develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their
corresponding outputs.

# Key Concepts Involved:

Prompt Engineering

Natural Language Processing (NLP)

Task Management

API Integration

Progressive AI Design Thinking

# Basic Instruction:

This is the most straightforward way to prompt an AI. You give it a list of tasks and ask it to organize or structure them, assuming it has the context or general knowledge to do so.

## Prompt:

"Organize the following tasks for today: Buy groceries, Finish project report, Call the dentist, Workout, Check emails."

##  Output:

Finish project report

Call the dentist

Check emails

Buy groceries

Workout

# Use:

Simple to-do list generation with default prioritization logic.

## Behavior:
Assumes general rules: deadlines > appointments > routines.

Doesn’t adapt to personal user preferences unless pre-trained.

## Real-World Value:
Quick, frictionless task prioritization.

Good for first-time users or simple apps.

# Example-Based Instruction:

Provide a few input-output examples before asking the model to perform a similar task. It helps the model infer your logic or preferences.



## Prompt:

"Here is how I like my tasks organized:

Tasks: [Pay electricity bill, Read 1 chapter, Jog]

Output:

Jog

Pay electricity bill

Read 1 chapter

Now organize: [Buy groceries, Finish project report, Call dentist, Workout, Check emails]"

## Output:

Workout

Call dentist

Finish project report

Check emails

Buy groceries

## Use:
Learning user preferences and customizing routines accordingly.

## Behavior:
Learns that time-sensitive tasks come first.

May mimic specific phrasing or order.

## Real-World Value:
Allows your app to "learn" from user-provided habits.

Supports recurring task routines (e.g., “Always meditate first”).

# Step-by-Step Reasoning:

Asks the model to explain its logic before giving the final output. This makes the decision-making transparent and often more accurate.

## Prompt:

"Organize these tasks for today and explain your reasoning:

[Buy groceries, Finish project report, Call dentist, Workout, Check emails]"

## Output:

# First, high-priority and time-sensitive tasks:

   Finish project report (deadline-driven)

   Call dentist (appointment windows)

# Then, medium-priority:

  Check emails (flexible timing but necessary)

# Finally, flexible tasks:

  Buy groceries

  Workout

# Final Order:

  Finish project report

  Call dentist

  Check emails

  Buy groceries

  Workout

## Use: 
  AI explains task reasoning, giving users transparency and trust.

## Behavior:
Gives detailed reasoning.

Builds trust and lets users modify based on logic.

## Real-World Value:
Useful in productivity coaching or mental wellness apps.

Users appreciate transparent AI.

# Personalized Assistant:
Define the AI's role or personality—like a coach, executive assistant, or productivity expert—and have it respond accordingly.

## Prompt:

"You are my personal productivity coach. Organize my daily tasks with priorities and include time estimates:

[Buy groceries, Finish project report, Call dentist, Workout, Check emails]"

## Output:

Daily Schedule:

 9:00 AM - Finish project report (2 hrs)

 11:00 AM - Call dentist (15 min)

 11:15 AM - Check emails (30 min)

 12:00 PM - Buy groceries (1 hr)

 1:00 PM - Workout (1 hr)

## Use: 
Structured day planner with time blocks and accountability.

## Behavior:
Adds context, breaks, personality.

Suggests wellness tips, routines, even motivational comments.

## Real-World Value:
Great for wellness apps or coaching platforms.

Gives a human-like feeling to the interaction.

# With Voice/Image Inputs:

Use non-textual input—voice, handwriting, screenshots—to extract tasks and structure them intelligently.

## Voice Input Example:

User: "I need to drop off the package, email my boss, do the laundry, and book my vaccine appointment."

Prompt (internally transcribed):

"Organize these tasks from voice input: Drop off package, Email boss, Do laundry, Book vaccine appointment."

## Image Input Example:
Image: A whiteboard with handwritten tasks:

“Dentist 3PM, Fix resume, Clean desk, Meds refill”

Prompt (internally OCR’d):

"Organize tasks from this list: Dentist 3PM, Fix resume, Clean desk, Meds refill."

## Expected Output:
Dentist 3PM

Fix resume

Meds refill

Clean desk

## Behavior:
Parses raw input (voice/image) into a structured plan.

Supports accessibility and natural user input.

## Real-World Value:
Great for mobile productivity tools.

Helps users avoid typing and stay hands-free.

# Table:

![Screenshot 2025-05-22 232122](https://github.com/user-attachments/assets/9374d2a8-23c6-431c-8b1c-4abf8fb5008d)


# Final Recommendation:

To create a scalable and intelligent task app, combine all five techniques:

Start with zero-shot for new users.

Let users train it with a few-shot example set.

Offer reasoning for trust and insight.

Add role-based personas for advanced planning.

Use voice/image inputs for convenience and accessibility.

# Result:

The Prompt is executed successfully


