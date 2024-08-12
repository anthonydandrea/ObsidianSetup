<%* 
const about = await tp.system.prompt("What is the meeting about?");
const attendees = await tp.system.prompt("Who is the meeting with?");
const noteTitle = tp.date.now("YYYY-MM-DD") + ' - ' + about + ' - ' + attendees;
await tp.file.rename(noteTitle);
await tp.file.move("Notes/Meetings/"+ noteTitle);
%>

## Discussion Points
- 

## Takeaways
- 

## Action Items
- 