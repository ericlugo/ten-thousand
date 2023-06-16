# Working Name: ten-thousand

## Proposal:

What problem does your app solve?

> A webapp aimed at helping users build long-term discipline and mindfulness.

Being as specific as possible, how does your app solve the problem?

> The building of discipline is done through task management, through the use of CBT task management tactics, and mindfulness is practiced daily through daily mindfulness exercises.

What is the mission statement?

> Our world is crazy, and busy.
> For people that suffer from any sort of mental health issue, that craziness is often exacerbated to an unmanageable degree.
> On top of that, research seems to be showing that a larger percentage of the population is being diagnosed with ADHD every year, a mental health issue that is often associated with many comorbid diagnoses.
> With all of this, we're often still expected to function the same as our neuro-normative peers and when we attempt to measure ourselves that way we tend to feel as though we are falling short.
>
> This project aims to show that things are not always as they seem.
> Everyone can use a little help.
> 
> **ten-thousand** features:
> - simple, minimalistic *Task Tracking and Management* aimed at getting things out of your mind right away so that you can focus,
> - *Leave it to Chance*, a creative way to circumvent the road-block of being overwhelmed when you don't know what task you should handle next,
> - *Daily Mindfulness Exercises* aimed at helping you to offload your feelings effectively before you end your day,
> - *Routine Building and Tracking* for training up the building blocks to live more freely,
> - and a *Brain Dump* to jot down any thoughts you might have, whenever you have them, so that you can always keep yourself focused.
>
> This isn't a cure-all, and I won't claim that this will fix everything. **ten-thousand** is just a passion project by one of the people that was diagnosed with ADHD as an adult, after struggling with it through childhood.
> As I've worked to improve myself, I've decided to make an app to do what *I think I need* after some long discussions with my therapist. My hope, is that maybe someone out there can benefit from it as well. By using **ten-thousand** every day, maybe we can build our way up to the way we want to live, strengthening our routines and habits, one day at a time.
>
> ---
> 
> *Interesting Reading*:
> 
> - Winston Chung, MD, MS; Sheng-Fang Jiang, MS; Diana Paksarian, MPH, PhD; Aki Nikolaidis, PhD; F. Xavier Castellanos, MD; Kathleen R. Merikangas, PhD; Michael P. Milham, MD, PhD  (2019). **Trends in the Prevalence and Incidence of Attention-Deficit/Hyperactivity Disorder Among Adults and Children of Different Racial and Ethnic Groups**. *JAMA Network Open* - <https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2753787>
> - Laura E. Knouse, Steven A. Safren (2010). **Current Status of Cognitive Behavioral Therapy for Adult Attention-Deficit Hyperactivity Disorder**. *Psychiatric Clinics of North America* - <https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2909688/>
> - Dusan Kolar, Amanda Keller, Maria Golfinopoulos, Lucy Cumyn, Cassidy Syer, Lily Hechtman (2008). **Treatment of adults with attention-deficit/hyperactivity disorder**. *Neuropsychiatric Disease and Treatment* - <https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2518387/>

## Features:

What features are required for your minimum viable product?

> - account creation/verification through email
> - task creation
> - task updating
> - task deletion
> - task sorting
> - task completion
> - daily message logging (with inclusion of completed tasks)

What features may you wish to put in a future release?

> - task scheduling
>   - "DUE NO LATER THAN..." the task can be set to be due on a certain day, meaning they must be completed no later than the set date
>   - "DO ON..." the task can be set to be done on a certain day meaning it must be completed by the end of day that day or will carry a mark that it is **!overdue!**
> - task display based on schedule (think rolling calendar view)
> - task picking from current scheduled tasks based on random selection
>   - optionally with "no later than" pool as "include tasks that are due soon"
>   - optionally with unscheduled pool as "include unscheduled tasks"
> - brain dump display by entry date
> - brain dump entry creation
> - brain dump entry updating
> - brain dump entry deletion
> - brain dump entry tag system
> - brain dump display by entry tags
> - routine creation
>   - tasks in routine with time it takes to complete routines
>   - expected routine start time (with estimated end time automatically calculated)
>   - ability to schedule reminders for routines
>   - completed routines show in calendar view
>   - scheduled routines show in calendar view

What do the top 3 similar apps do for their users?

> - allow convenient restructuring of tasks and pulling from various sources like google calendar
> - kanban style task sorting
> - reminders for task completion

## Frameworks - Libraries:

What 3rd party frameworks/libraries are you considering using?

> FrontEnd: Ionic with React
> 
> BackEnd: NodeJS, Fastify*, GraphQL, PostgresQL
> 
> **\*** = *potential use*
