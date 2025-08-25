# CS230-completed-software-design
Reflection: The Gaming Room Software Design Document

Who was the client, and what were their requirements?
The client, The Gaming Room, wanted to expand their existing Android game, Draw It or Lose It, into a multi-platform distributed environment. Their requirements included the ability to support multiple simultaneous game instances, manage unique identifiers for players and teams, ensure secure user access, and provide a scalable architecture for deployment across operating systems.

What did I do particularly well?
I did well in breaking down the software requirements into clear architectural components. I was able to analyze each operating platform—Windows, macOS, Linux, and mobile—and compare their strengths and weaknesses for deployment. This helped shape my recommendations for the most appropriate platform choices. I also communicated technical ideas in a way that remained understandable for both the client and development team members.

What about the design document process was most helpful?
Working through the design document forced me to think about structure before code. This included considering scalability, memory management, and distributed systems upfront. Having the design mapped out meant I could approach development with fewer surprises, since the foundation was already logically planned.

What would I revise if I could?
If I could revise one part, I would expand the security and authentication section. While I mentioned basic authentication and secure endpoints, I could have gone deeper into future-proofing with role-based access control (RBAC) and token-based authentication strategies. That addition would improve the robustness of the document.

How did I interpret and implement user needs? Why does it matter?
I translated user needs into design choices by focusing on their main goals: multi-platform support, scalability, and smooth gameplay. For example, since users expected seamless gameplay, I prioritized efficient memory and storage management techniques. It’s important to consider the user’s needs first because software that does not align with end-user expectations risks failure, regardless of technical merit.

How did I approach designing the software, and what strategies will I use in the future?
I approached the design by analyzing requirements, comparing system architectures, and documenting trade-offs between platforms. I used structured analysis (breaking the problem into smaller components) and comparative evaluation (analyzing OS architectures). In the future, I would continue to use this structured approach, but I’d also incorporate more modeling techniques such as UML diagrams and user stories to bridge the gap between design and implementation more effectively.
