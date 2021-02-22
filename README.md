# journey_to_vim_with_vscode

my journey to learn VIM with my primary code editor VSCode


## V I M
### shortcuts

    Keys:            Description:

    :q               quit editing
    :wq              write & quit
    :w               write/save file
    :q!              quit without saving
    :set number      view line number of the file
    :![terminal cmd] execute terminal command from VIM

    i                insert mode before cursor
    a                insert mode after cursor
    I                insert mode beginning of the line
    A                insert mode ending of the line
    o                insert mode with a new line down
    O                insert mode with a new line up
    gi               insert mode from last position
    v                visual mode
    V                visual mode select by line
    ctrl + v         visual block mode
    esc              normal/command mode
    ctrl + c         normal/command mode

    h                move cursor to left
    j                move cursor to up
    k                move cursor to down
    l                move cursor to right

    gg               go to start of file
    G                go to end of file
    {                go to up a block
    }                go to down a block
    ctrl + u         go to up half a page
    ctrl + d         go to down half a page

    w                move cursor to next word
    W                move cursor to next word after a space
    b                move cursor to previous word
    B                move cursor to previous word after a space
    e                move cursor to end of the next word
    E                move cursor to end of the next word after a space
    ge               move cursor to end of the previous word
    gE               move cursor to end of the previous word after a space
    ^                move cursor to 1st word of the line
    g_               move cursor to end of last word of the line
    0                move cursor to start of the line
    $                move cursor to end of the line
    t[character]     move cursor to before the character
    f[character]     move cursor to the character
    ;                repeating forward search
    ,                repeating backward search
    %                move cursor between two brackets
    :[any number]    move cursor to line number
    *                move cursor to repeating word

    r                replace a character
    R                replace multiple characters
    x                delete a character
    dd               delete/cut a line
    dw               delete word
    d[move cursor]   delete to the new cursor position
    dt[character]    delete up to the character
    D                delete rest of the line from cursor position
    cw               change word and go to insert mode
    C                delete rest of the line and go to insert mode
    ct[character]    delete up to the character and go to insert mode

    y                copy selected characters/block
    yy               copy a line
    p                paste in down
    P                paste in up
    +p               paste from the clipboard

    u                undo
    ctrl + r         redo

    zz               make cursor position center of the screen
    ~                swap case of the character
    g~~              swap case of the line
    .                do the last command again
    [number][cmd]    do the command for the number of times
    >                indent right
    <                indent left

    /[word]          search for all repeating word forwards
    ?[word]          search for all repeating word backwards
    n                move cursor to repeating word
    N                move cursor to repeating word
    s[char][char]    search for matching character
    S[char][char]    search for matching character backwards


    q[character][cmd sequence]q        record a macro to the character
    @[character]     implement macro

    gd               jump to definition
    gf               jump to file in a import

    :sp              split tab horizontally
    :vsp             split vertically
    ctrl + w + hjkl  move cursor to split

    :tabnew [file]   open file in new tab
    :tabp            go to previous tab
    :tabn            go to next tab

    ds'              delete surrounding
    cs'"             change surrounding with "

    gb               add another cursor to the repeating word
    gh               hover over cursor


### References:

    [barbarianmeetscoding](https://www.barbarianmeetscoding.com/blog/boost-your-coding-fu-with-vscode-and-vim)
    ---
    
    [Fireship](https://www.youtube.com/watch?v=-txKSRn0qeA&ab_channel=Fireship)
    ---
    
    [BenAwad](https://www.youtube.com/watch?v=IiwGbcd8S7I&ab_channel=BenAwad)
    ---
    
    [MissingSemester](https://www.youtube.com/watch?v=a6Q8Na575qc&feature=emb_rel_pause&ab_channel=MissingSemester)
    ---
    
