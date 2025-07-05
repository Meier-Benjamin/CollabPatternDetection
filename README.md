The use of collaborative robots ("Cobots") enables companies to open up new possibilities in manufacturing, such as the ability to customize products more easily, reduce costs, or deploy workers more
efficiently. Collaborative Patterns categorize and describe the work between humans and cobots. The
aim of this work is to analyze the current state of research on Human-Robot Collaboration (HRC) and
to automatically recognize Collaborative Patterns between different actors in event logs.
For this purpose, a systematic literature search was carried out in common scientific databases.
Furthermore, a mining algorithm for recognizing Collaborative Patterns was designed, developed,
implemented in Python and evaluated using predefined use cases.
During the research, it was found that there is no uniform definition of patterns, but a particularly
common definition ("Coexistence", "Synchronized", "Cooperation", "Collaboration"). Recognition of
these patterns was therefore implemented in the algorithm.
The developed algorithm allows the successful recognition of patterns in an event log and can assign
corresponding patterns to individual activities within a case.
The limitations of the algorithm lie in the lack of ability to separate activities in terms of space, which
would be advantageous for some patterns. However, this is caused by data availability issues in
traditional event logs. A possible remedy is the use of generative AI or the collection of additional
positioning data for the event log.
The work underlines the importance of research in the field of HRC and, in particular through the
development of the algorithm, makes a further contribution to a better understanding of how different
actors work together in a production scenario.
