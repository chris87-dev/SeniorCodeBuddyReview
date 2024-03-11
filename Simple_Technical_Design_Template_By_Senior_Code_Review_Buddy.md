# Simple Technical Design Template By Senior Code Review Buddy

_Replace with your title_

Author: _Your Name (your@email.com)_

Date: _Fill In_

Status: _Draft?/Pending?/Approved?/Rejected?_

**_Top Level Note: This is just a template, change it to what works best for you. If you don’t like a certain part, drop it. If there is a section you think is missing, add it. I only hope that this provides a helpful starting point._**

**_If you have any questions or suggestions, feel free to reach out to chris@seniorcodereviewbuddy.com_**


[TOC]



## Problem Summary

_In a few sentences, provide a brief summary of the problem you are looking to solve. Try to describe what impact this problem is currently having and make clear why this is a problem people should want to solve now. Don’t worry about the solution yet, just focus on the problem you want to solve._

_Feel free to provide links to additional sources that can help a reader fully understand the problem. _

_Here are two examples:_



1. _Due to overall growth of the number of users, we are trying to write more data to the database than it’s capable of processing at once. This is resulting in users hitting timeouts when they attempt to save their data, with the users getting frustrated and the data not getting saved._
2. _Our platform currently only supports text based communications and as part of our 2024 Q4 OKRs (link to OKRs) we want to add audio based communication. These voice communications should be fully synchronous. See the Product-Requirement Document here for exact details of what the product should look like for users._


## Solution Summary

_In a few sentences, explain what solution you are proposing and what it’ll look like. If there are any major points that someone should be aware of, it is probably worth calling them out here. You’ll go into more detail about the solution in the next section, so this is more the elevator pitch. _

_Here are two brief examples of what this could look like:_



1. _To improve throughput of the database, we’ll stop using X (which can only run one instance at a time) and start using X2 (which can scale up to as many instances as we need). _
2. _To support audio based communications, we’ll be integrating a new third party library, AudioParty. Since these communications will be synchronous, versus our existing async text chats, we’ll be creating a complete new code repo to handle these interactions. The existing “Start Chat” functionality will be pulled into a new server, which will then route users to the required sync or async server as needed._


## Detailed Solution

_Here you’ll provide more detail on what exactly your solution will look like. It can be tricky to figure out the right level of detail. Don’t try to solve every problem that might arise, instead try to just address the major known problems (anything that might be hard to solve, or generate a challenging code review comment). _


### Impacted Code

_It can be helpful to provide links to the code that you expect to be changed while implementing this document. These could be links to different functions, files, folders or even repos, depending on the scope of the document and size of the change._


### Testing

_How will this feature/change be tested? Just unit tests? Will there be integration tests? Will it require manual testing to be added to the standard release testing process?_

_If there is a lot of manual testing required, it might be best to pull that out into its own document._


### Monitoring and Success

_How will people know when this design has been successfully completed? What metrics should be improved (decrease in timeout errors?) or what new metrics should be added to dashboards to watch? _

_This is an important section to consider, if you don’t have a clearly enunciated definition of what success looks like. If people haven’t aligned on exactly what problem is being solved, it can be hard to agree on the best solution._


## Alternatives Considered
_What alternatives were considered before settling on the selected solution? For each alternative, provide a brief description of that solution and explain why it’s not as suitable as the chosen solution. This section isn’t just intended for readers today when approving the document, but it can also be very helpful in the future when trying to understand or remember why a certain design was chosen._


## References

_If there are any additional references that you think a reader could find helpful, add them here. It could be other design documents, meeting agendas or links to other pages in the organization._


## Approvals

_When working on a design that’ll have an impact on others (which most designs will), it’s helpful to get sign off/approval from the other folks, to ensure they are aware of what you are doing. This can also help ensure there aren’t gotchas that you missed._


<table>
  <tr>
   <td>Name
   </td>
   <td>Date
   </td>
   <td>Comments
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>

