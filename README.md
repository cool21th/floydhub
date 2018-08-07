# floydhub

If you don't have GPU, you can use cloud GPU like FloyedHub

## example for mac
1. floyed install

    pip install floyd-cli

2. Create new project(Web page)


3. Login(terminal)

    floyd login

4. connect folder 

    floyd init {name}/{project name}
    
5. floyd run

    floyd run {insert-command-here}

    ##To use GPU
    
    floyd run --gpu {insert-command-here}

    ##To use a different environment
    
    floyd run --gpu --env pytorch {insert-command-here}
