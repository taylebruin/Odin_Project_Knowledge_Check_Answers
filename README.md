# Odin Project Knowledge Check Answers
This readme is for me to store my answers to the knowledge check portions of the Odin Project

## Asking For Help | Foundations Course
1. Name at least one thing your question should always include.

Answer:

Always provide your code and the surrounding context. In other words don't ask vague questions make your questions as specific as possible about the problem you are trying to solve.
For example, dont ask "how do I complete step 5?" ask I am getting an error on line 12 I am trying to getting it to do x but it returns y or an error for example.

2. Describe the “XY Problem”.

Answer:

The XY problem is asking about your attempted solution to a problem rather than asking about your actual problem. For example lets say you want to understand how to go about getting the file extenstion of a file.
Your solution could be to grab the last three characters of the file name not realizing that there could be files with different extention lengths. When you ask "How do I get the last three characters of a file you
will get an incorrect answer to your actual problem.

Example:


> n00b: How can I echo the last three characters in a filename? <br>
> feline: If they're in a variable: echo ${foo: -3} <br>
> feline: Why 3 characters? What do you REALLY want? <br>
> feline: Do you want the extension? <br>
> n00b: Yes. <br>
> feline: There's no guarantee that every filename will have a three-letter extension, <br>
> feline: so blindly grabbing three characters does not solve the problem. <br>
> feline: echo ${foo##*.} <br>


3. Describe three attributes of a “help vampire”.

Answer:

Help Vampires are people that are simply looking for others to solve the problem for them. They often don't realize
what they are doing but they do it anyways. While there are several potential attributes listed below I think the three most common
that I have seen and done at times are as follows. First asking questions to rapidly often it is easy to simply ask someone who knows
the answer rather than try and solve it yourself. Sometimes asking is the write solution but when you are trying to learn taking more
time to solve the problem will help you more in the long run. Second not Googling, I think the problem is often people don't know how
or what to Google they try one thing and when it doesn't immidetly fix their problem they give up. Third is specificity oftentimes it 
is helpful to be almost too in depth on what you are trying to do and what you have done. In my work I have even shared sources I have 
found to help explain what I am trying to do and I have found oftentimes that someone just rephrasing what I already can help me overcome 
obstacles.

Does he ask the same, tired questions others ask (at a rate of once or more per minute)? <br>
Does he clearly lack the ability or inclination to ask the almighty Google? <br>
Does he refuse to take the time to ask coherent, specific questions? <br>
Does he think helping him must be the high point of your day? <br>
Does he get offensive, as if you need to prove to him why he should use Ruby on Rails? <br>
Is he obviously just waiting for some poor, well-intentioned person to do all his thinking for him? <br>
Can you tell he really isn’t interested in having his question answered, so much as getting someone else to do his work? <br>
The also ask impossible questions for example, "how do I build a forum?" <br>
