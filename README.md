# rjm_games_V2
HTTP Game Server
utilizes game_engine from version 1
complete redesign


5/13/2022  Getting there.  Able to request and render files all the way to start page.
            Currently, debugging quiz.py and quiz_view.py.
            Still need to fix the issue with having to stop loading page and re-requesting
            page to load.  This may have something to do with favicon.ico.  Might need to
            send a fake (or real) icon.  May want to make it non-cacheable, so that it is
            predictable, when the browser will request it.
            
           Able to load quiz with single question.  Still need to solve the loading problem.
           Considering trying to read after each send, then setting a short timeout on the
           socket.  This will have to be contained in a try-except block, but may be
           necessary to hunt and kill favicon.  
