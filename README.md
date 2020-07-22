# alfred-workflow-fantastical

Simple Alfred Workflow to add calendar appointments in [Fantastical](https://flexibits.com/fantastical) 📅.

This workflow acts a proxy to Fantastical powerful Natural Language Processing (NLP) Capabilities. 

## Usage

> Trigger work `cal`

<img width="683" alt="Screenshot 2020-07-22 at 14 42 19" src="https://user-images.githubusercontent.com/550726/88183717-b7f16f00-cc29-11ea-9c1f-f7190e23c426.png">

`cal Call with Adam Smith tomorrow at 12:00`

<img width="652" alt="Screenshot 2020-07-22 at 14 42 44" src="https://user-images.githubusercontent.com/550726/88183727-b9bb3280-cc29-11ea-928a-e77a818cc48d.png">

Here’s the general format we recommend you use when adding things using natural language into Fantastical”

`[event name] at [location] [date/time] [alert] [URL] [calendar name]`

Here are some examples of adding things using natural language in Fantastical using that format:

 - Grocery shopping at Woodman’s Friday at 5pm
 - Soccer practice Tuesday at 6
 - Family vacation from July 1-8
 - Lunch with Josh at Joe’s Sandwich Shop 1:30 Monday
 - Toby’s birthday every year on 12/23
 - Piano lessons Mondays and Thursdays at 5-6pm from 1/21 to 5/23
 - Haircut June 24 10am alert 30 minutes
 - Flight 997 on Saturday 3pm EST to 6pm PST
 - Here are some tips to help you take your natural language entries to the next level.

## Assigning an event to a specific calendar
You can specify which calendar you’d like to add the event to by typing a slash (/) followed by the calendar name at either or the beginning or end of your sentence. For example:

To add an event to your Work calendar, add /w
To add an event to your Personal calendar, add /p
You can also add tasks to your Reminders lists this way.

If you have more than one calendar or reminder list that starts with the same letter, the next letter in the name that is different can be used to differentiate them.

## Specifying a Reminder
By default, Fantastical will create an event when you add it by typing a sentence using the natural language engine. You can change this and tell Fantastical to create a reminder instead by clicking on the toggle slider at the top-right of the new event area, but you can also tell Fantastical you’d like to create a reminder by starting your sentence with:

 - reminder
 - todo
 - task
 - **√ (⌥V)

You can also quickly set the priority of a new reminder by adding exclamation points to the end of your reminder. More exclamation points will increase the priority of the reminder. For example

`task Look through TSS natural language guide !!!`

## Add a Repeating Task
One common event type that isn’t obvious how to add using natural language is repeating tasks. You can always modify the details of the event as you add it via the Fantastical interface, but in our opinion that kind of takes the joy out of adding things using the natural language parser. So to add a repeating event without taking your hands off the keyboard, use a : followed by the interval you’d like to use:

 - daily
 - weekly
 - monthly
 - yearly

For example:

`coffee w/ Shawn tomorrow 7am :weekly`

You can also a phrase like “every Tuesday” when adding an event:

`coffee w/ Shawn every Tuesday at 7am`
