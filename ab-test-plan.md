The page and the single element you are changing, with the text or a description of A and B.
This experiment will test whether doubling the word count of the homepage’s opening paragraph increases AI visitors’ intention to click a donation category link.
Version A (Control): The existing homepage with its original opening paragraph.

“Not sure where to donate your extra clothes, books, or household items? Our Iowa City donation guide helps you understand your options and prepare your items for a second life.”

Version B (Variant): The same homepage with an opening paragraph containing twice as many words as Version A. The additional text will provide more detail about the guide’s purpose and the donation information available.

“Not sure where to donate your clothes, books, furniture, or household items? Our Iowa City donation guide helps you explore donation options, find places that accept your items, and prepare your belongings for a second life. Whether you are cleaning out your closet or decluttering your home, this guide makes it easier to give your unwanted items a new purpose.”

Your hypothesis, written as a prediction that could turn out wrong, and the reasoning behind it.
I chose to test the length of the opening paragraph because it is one of the first elements visitors see and may influence whether they continue exploring the website. While a shorter paragraph allows visitors to reach donation categories more quickly and avoids information overload, a longer introduction may provide additional context about the website’s purpose and resources.

I hypothesize that doubling the opening paragraph’s word count will increase AI visitors’ intention to click a donation category link. The additional information may help visitors understand the guide’s usefulness and encourage them to explore donation options.

The model, the persona, the exact prompt, and how each trial is assigned to A or B.
AI Model: GPT-6 Sol, Plus, thinking off and web search off, using the same model configuration and settings for all trials. 
Persona: Iowa City resident with gently used clothing, books, and furniture who wants to find local donation options.

Exact prompt:
“You are an Iowa City resident with gently used clothing, books, and furniture that you would like to donate. You are looking for local donation options. Read the provided homepage of the Iowa City Donation Guide. Based on the homepage, would you click any of the donation category links to find more information about where to donate your items? Answer Yes or No, followed by exactly one sentence explaining your decision. Base your answer only on the homepage provided.”

Trials: Each trial will take place in a fresh conversation with no memory of previous trials. Both versions will be provided as complete page text in the same format, with only the opening paragraph differing.

Before testing, 50 Version A and 50 Version B assignments will be randomly shuffled using Google Sheets’ RAND () function. The assignment order will be saved before collecting data.

Your one primary outcome and how it is measured.
The primary outcome is AI visitors’ stated intention to click a donation category link.
Yes = 1: The visitor indicates they would click a donation category link.
No = 0: The visitors indicates they would not click a donation category link.
The percentage of Yes responses will be calculated separately for each version.

The sample size you will reach before stopping, and the date you expect to reach it.
The experiment will include 100 trials, with 50 for each version.
Planned launch: November 17, 2026
Expected completion: November 24, 2026
All trials will be completed as planned, and AI responses will be saved.

The comparison you will make, and what result would count as support for your hypothesis.
The percentage of Yes responses in Version B will be compared with the percentage of Yes responses in Version A. The difference will be calculated as Version B’s Yes response rate minus Version A’s Yes response rate.

A two-sided test for the difference between two proportions will be conducted using a significance level of 0.05.

The hypothesis will be supported if Version B produces a higher Yes response rate than Version A and the difference is statistically significant (p < 0.05). 
