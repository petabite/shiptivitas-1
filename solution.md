#### Solution
- To implement drag and drop, I used the Dragula API.
- To make sure that all the jobs showed up in the 'backlog' swimlane, I changed all statues of each client in the getClients() function to equal 'backlog'.
- To implement the color changing when the job is dropped in another swimlane, I used the Dragula 'drop' event listener and pulled the swimlane's title from the DOM and respectively changed the class name of the job to the correct corresponding color(ex: if the job was dropped in 'completed', the job would have the 'Card-green' class toggled so that the background color would change to be green).
