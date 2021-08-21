## Project Description

The artifact chosen for this milestone is a demonstration of SQL injections and the mitigation thereof. It was created in May of 2021 as a part of CS-405, a course on secure coding in C++. It is included in my ePortfolio primarily because I thought I could do it better without the constraints of the original assignment. Specifically, the original assignment called for inspecting the SQL statement passed in for signs of injection and returning an error if these were found, and mitigated only specific types of SQL injection, specifically those using an OR clause. While this certainly serves to demonstrate SQL injections and the basics of how they might be detected, it is hardly common practice these days to assemble SQL queries by hand without preparation, and it is quite limited in its scope. I wished to turn the assignment into an overall demonstration of how many types of SQL injection can be prevented entirely through the use of prepared statements.


## Skills demonstrated, improvements made

I believe the improved artifact shows my skills at learning and deploying entirely new API functions (having not used sqlite3’s prepared statements before) as well as in restructuring existing code to fit a new purpose while keeping major parts of it relatively unchanged and recognizable. The improvements include the separation of the run_query function into two functions, one which acts like the unmodified assignment code in that it runs unprepared queries with no injection detected or mitigation, and one which uses modern prepared queries through sqlite3_prepare_v2 and related functions. The sql query and the username passed to the query were split in the code so that these can be passed to both the prepared and unprepared query functions in the same manner. 

My plans going forward largely include better documenting, commenting, and cleaning up the code, and perhaps demonstrating more and different types of injections and how they can be mitigated through prepared queries. 


## Skills learned and expanded

In the process of enhancing the artifact, I learned much about how sqlite3 handles prepared statements, as well as how to use default arguments to functions, and how to rework code to fit new parameters. I also learned the dangers of changing too much about a project at once: Due to my greater familiarity with MariaDB/MySQL than SQLite3, I originally had attempted to redo the entire project using the MariaDB C++ Connector instead of SQLite3. I found that this connector has some major existing bugs that prevent it from working properly and attempting to debug these, work around them, and figure out why they were happening took valuable time away from completing the assignment itself. I eventually gave up and went back to the original SQLite3 based code, and while working with a C library in C++ is sometimes a bit painful, it went faster and cleaner overall.


## Link
https://github.com/Dizzy611/SNHUSQLInjectionePortfolio

