Virtual servers that execute jobs from workflows
1. GitHub -Hosted (standard)
    Windows & ubuntu, mac

    maged service.
    A VM is scoped to a job:
     steps share the vm but jobs dont by default each job receives a clean vm instance.

2. Self-Hosted
    Run workflows on (almost) any infrastructure of your choice.
    Full control over the VM infrastructure
    Its not managed, meaning we need to take care of OS patching, Software updates, among other ops tasks.
    jobs do not necessarily have to run on clean instances. 


    Dont use self-hosted runners in public repositories!
