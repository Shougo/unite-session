unite-session.vim
=================

Description
-----------
Session source for [unite.vim](https://github.com/shougo/unite.vim).

Installation
------------

Recommended installation is via NeoBundle. 
*  [NeoBundle](https://github.com/shougo/neobundle.vim)
  *  `NeoBundle 'Shougo/unite-session'`

Usage
--------
1. Save the current session as a new session via `:Unite session/new`
2. Edit and load sessions via `:Unite session`


Commands
--------

:UniteSessionSave session-name
                Saves session data in session-name.
                Automatically saves over session-name if it exists.
                If session-name is omitted, |v:this_session| or
                |g:unite_source_session_default_session_name| is used.

:UniteSessionLoad session-name
                Loads session data from session-name.
                If session-name is omitted, |v:this_session| or
                |g:unite_source_session_default_session_name| is used.
                If session data is not found, it is created.




