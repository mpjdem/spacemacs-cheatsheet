# General
Quit                      SPC q q
Terminal                  SPC SPC term
Shell command             SPC ! <command> 
 
# Vim modes
Insert before             i
Insert after              a
Insert line start         I
Insert end of line        A
Insert new line below     o
Insert new line above     O
Insert substitute char    s
Insert substitute line    S

Visual char               v
Visual line               V
Visual block              CTRL-v 

# Move cursor
Line down/up              j k
Char left/right           h l
Line start/end            0 $
First non-ws char         ^
Blank line                { }
Word forward/backward     w b
Buffer start              gg
Buffer end                G
Screen head/mid/end       H M L

# Move screen
Line down/up              CTRL-e CTRL-y

# Editing
Delete char               x
Delete char & insert      s

Delete word               dw
Delete line               dd
Delete to end of line     D
Delete <move>             d <move>

Delete word & insert      cw
Delete line & insert      cc
Delete to end & insert    C
Delete <move> & insert    c <move>

Paste after/before        p P

Copy selected             y
Copy line                 yy
Copy to end               Y
Copy <move>               y <move>

Replace char              r
Replace first in line     :s/<pat>/<repl>
Replace all in line       :s/<pat>/<repl>/g
Replace again             &
Replace all               :%s/<pat>/<repl>/g
Replace all but confirm   :%s/<pat>/<repl>/gc

Undo/redo                 u CTRL-r
Join with next line       J

# Search
Forward                   / <pat>
Backward                  ? <pat>
Next/previous             n N
Search word               #
Clear highlight           :noh
Find parenthesis match    %

# Windows
Split right               SPC w /
Split down                SPC w -
Next                      SPC w TAB
Delete                    SPC w d
Switch to 2               SPC 2

# Files
Recent                    SPC b h r
Tree                      SPC f t
Find                      SPC f f
Save                      SPC f s

# Buffers
New                       SPC b N
Switch                    SPC b b
Next                      SPC b n
Previous                  SPC b n
Delete                    SPC b d
Send to window 2          SPC b 2
