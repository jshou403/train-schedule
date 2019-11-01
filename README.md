# train-schedule

[About] This Train Scheduler takes in user input and stores it on Firebase, which allows viewers to see the schedule in real time. Moment.js uses the data retrieved from Firebase and converts the data stored to times relative to the viewer so no matter who is looking at the schedule, they are able to see the time of the next train and how many minutes away it is from that moment. 

[Link] https://jshou403.github.io/train-schedule/

[Languages] Moment.js, Firebase, Javascript, jQuery, HTML/CSS

[MyComments] To improve functionality of the train scheduler, the input fields could be cleared once the information is submitted or there should be a confirmation request for the scheduler to check the info before the new train is added. Another is to convert the train frequency and time until next train from minutes to hours if over 59 minutes. A more complex improvement would be to having a train start and end date so that the train disappears from the schedule once it stops running, for example, a train that runs more in the winter to a ski resort. 