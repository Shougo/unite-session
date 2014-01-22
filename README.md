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

Save session data in `<session-name>`. This will override the session
if it exists.

    :UniteSessionSave <session-name>

Load a session by `<session-name>`. This will create a new session with 
the given name if none exists.

    :UniteSessionLoad <session-name>




