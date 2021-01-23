To switch between Steam-enabled mode and Epic Online Services mode:

    In Config/DefaultEngine.ini at line 31:

    To use Steam:

            [OnlineSubsystemSteam]
            bEnabled=true

    To use Epic Online Services:
        
            [OnlineSubsystemSteam]
            bEnabled=false
        