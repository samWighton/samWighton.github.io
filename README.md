# Sam Wighton 

This page is a draft - there may be errors or missing information

Sam Wighton is a programmer with skills focused on system programming and learning from data

[Professional Career](/#professional-career) |
[Hobbies](/#hobbies) |
[Side Projects](/#side-projects)

## Professional Career

### Current Employment at [Accelo](https://www.accelo.com/)

Employed as a full stack developer.

This job involves writing code and unit tests. Frequently with a Test Driven Development approach. Sam works on projects, bug fixes and develops internal tools.

Sam is specializing in the code that enforces the business logic of permissions and authorisation. Sam is also often given work that relates to processing graph-style data.

Accelo uses the Elastic stack to provide prompt responses to user actions.

Work also involves monitoring the behaviour of code in production. Infrastructure provided by (AWS). 

Sam's work at Accelo also involves statistical analysis of the performance of different versions of code while seeking to improve performance. 

Sam is able to work quickly. Here is a screenshot of his most recent week long sprint:
![Sprint Screenshot](images/end_of_week_screenshot_small.png)
(Week ending 2017-07-07. All but two tasks on screen were started that week)

Programmers at Accelo are expected to automate processes to reduce workload. Sam has written static analysis tools to assist in refactoring the codebase.

### Previous Employment at [IMB Bank](http://www.imb.com.au/)

Employed as an Analyst. Also worked as a developer.

Worked on the core legacy system.

Created interoperability between the core system and newly installed [teller cash recyclers](https://arca.com/solutions/cash-recycling).

Created web front ends for existing databases.

Wrote a parser to convert human readable database schemas (for the core noSQL database).
This allowed the creation of machine readable schemas and web-based documentation.

Promoted the use of version control (now in place) and automated unit testing.

Met up with a board member of the bank to discuss the modernisation of the development process several times. Even after resigning.

### Contract work

In addition to ongoing employment, Sam also does contract work. (Australian Business Number: 42530866880)

Sam has worked for [Tradimo](https://learn.tradimo.com/about) as a programming coach. This work involved meeting with traders to discuss how automation through programming can assist with trading. Programs to assist with trading were created and distributed on the site. 

Working for the University of Wollongong and related organisations, Sam created programs to assist in the collection and processing of data for academics. His work has been acknowledged in three papers, one of which he is co-author.

The program written for the above mentioned paper involved the tracking of maggots observed through thermal and visible-light cameras. 

Sam wrote a data conversion program for accountancy firm [PKF Lawler](https://www.pkf.com.au/) to assist with government compliance.

After complaints about sound levels at an auditorium, Sam measured samples of the audio energy levels, created a model of the energy distribution and presented a report to managers. 

### Tutoring

Sam has been providing science, mathematics and programming tutoring for secondary school level students for 6 years.

### Public Speaking

Sam has given several programming related talks:

Sam has been invited to speak to the developers or owners of companies on four occasions. These talks were on the topic of machine learning; with the content personalised for each company.

Sam has also talked at meetups and events, and is scheduled to talk at two more events this year.

### Hackathons, Meetups and Conferences

Sam has participated in a few hackathons. His team won 'Best indi Game' at the most recent 'Hackagong'.

Sam has also participated in internal hackathons at Accelo, and has worked with sponsors and promoters at public hackathons.

Sam assists in the running of a Wollongong based Meetup. He has given a talk 'A.I. for Business' at the meetup.

Both for eduction and networking, Sam attends conferences such as the AWS Summit regularly. 

## Hobbies

### Rock Climbing

Sam takes advantage of having an [indoor climbing gym](http://hangdog.com.au/) within walking distance of work.

Climbing more complex routes takes skill and planning, not just physical strength.

There is great satisfaction to be had after achieving a goal through continued persistence.

### Audio Engineering
![A local band Sam mixes for](images/band.jpg)

The image above is a local band that Sam mixes for once a month.

Part hobby, part volunteering, part professional work. Sam has been recording and mixing audio for more than 14 years.

Skills that have been acquired in this field have found use in other areas of Sam's life. The audio signal chain is a helpful mental model when considering time-series data analysis. The principals of component extraction from a signal are often similar across disciplines.

Sam has written many programs related to processing and analysis of audio data. 

## Side Projects

### Kaggle Competitions 
![Kaggle Screenshot](images/kaggle_screenshot.jpg)

On the left is a satellite image of the Amazon rainforest. The image was provided as part of the data set from a [Kaggle competition](https://www.kaggle.com/c/planet-understanding-the-amazon-from-space).
The image on the right is part of the output of a program written by Sam. Colour indicated the algorithm certainty of water (Cyan indicates strong certainty)

This project was undertaken for enjoyment and was written without any machine learning, statistics or maths libraries.
The programming language [Rust](https://www.rust-lang.org/en-US/) was used. A .PNG file parser was written and the pixel colour information of the 40,000 images was analysed.

The goal of the competition was to tag each image in the test set of images with correct labels according to the content of the images.
Enabling the program to output confidence values at a per-pixel resolution provided great insight into the performance of the algorithm during development. 

The following shows an example of such output, (at this stage of development, different techniques were being implemented for each tag type) 

![Kaggle Screenshot 2](images/kaggle_multi.png)

### Cloud based Audio mastering

Traditionally, analogue [outboard gear](https://en.wikipedia.org/wiki/Outboard_gear) has been used to modify audio signals.
Sam has written many stand-alone tools that can perform similar functions to outboard gear.

Applying machine learning to the audio signal chain has created opportunities for new 'content-aware' tools.
Sam has been writing such tools to be hosted by AWS as a service that could be useful to content creators who want a simple solution.

### Machine Learning research

Sam is constantly reading the research of others in the fields of Machine Leaning.

Although comfortable using libraries such as TensorFlow, Sam enjoys developing his own techniques for data analysis.

Both as a source of education and enjoyment, Sam will seek out problems that may benefit from a machine learning solution ( such as the [Numerai Hedge Fund](https://numer.ai/) ) and write analysis tools from first principals. A current effort is investigating pairwise dependence of parameters while calculating probability densities to help avoid overfitting due to the 'curse of dimensionality'.

As is is helpful in modelling many real world systems; Sam has been focusing his recent research on Graph Theory.

The following describes the concept of some of Sam's current research:
Data structures and analysis techniques are being investigated

In some systems, there is value in maintaining the current state of an entity. 
In such a system, it is then also valuable to modify the system to reduce the probability of the entity changing state. 

Activities and communication in this system can be modelled as a series of events describing the creation and modification of edges and nodes in a graph. 

The behaviour of an entity in this system is understood as a higher level model describing sequences of actions of the entity.

If the system is optimised for maintaining the state of these important entities, then behaviour of any entity that disrupts such a steady state would be considered anomalous and unwanted.

This project would seek to predict future state changes of nodes (with a high degree of centrality) by modelling the influence of behavioural anomalies in time series graph data. 

Such a system could suggest the 'lowest cost' solution to returning the system to a more desirable state.

