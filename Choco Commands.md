# Chocolatey

## Key commands

-[Outdated](https://docs.chocolatey.org/en-us/choco/commands/outdated)

    choco outdated

-[Upgrade all installed packages](https://docs.chocolatey.org/en-us/choco/commands/upgrade)


    choco upgrade all 
    
    choco upgrade all -y

-[List installed packages](https://docs.chocolatey.org/en-us/choco/commands/list)

    choco list --localonly


Disable prompts globally

    choco feature enable -n=allowGlobalConfirmation

Bypass prompt single execution
    
    choco install XYZ -y

Choco Gui

    choco install chocolateygui 
