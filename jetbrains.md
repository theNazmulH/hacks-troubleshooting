## Jetbrains hacks and troubleshooting

`Issue#1`

> Cannot connect to already running IDE instance at 945" error   
> typically occurs when IntelliJ IDEA detects that another instance of  
> the IDE is already running and prevents you from starting a new one.



##### Solution:

Terminal Command

    kill -9 [pid]

where [pid] is the process id. In this example, it is 945

Final terminal command: 

    kill -9 945
