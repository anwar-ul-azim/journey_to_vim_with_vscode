# journey_to_vim_with_vscode

my journey to learn VIM with my primary code editor VSCode

## V I M

### shortcuts

    Keys:            Description:

    :q               quit editing
    :wq              write & quit
    :w               write/save file
    :q!              quit without saving
    :![terminal cmd] execute terminal command from VIM

    :set number      view line number alternative vimrc

    .                repeat the last command
    [number][cmd]    do the command for the number of times

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

    R[character]     replace mode and replacing character

    esc              normal mode
    ctrl + c         normal mode
    jj               normal mode

    h                move cursor to left
    j                move cursor to up
    k                move cursor to down
    l                move cursor to right

    :[any number]    move cursor to line number

    zz               make cursor position center of the screen
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

    0                move cursor to start of the line
    ^                move cursor to 1st word of the line
    $                move cursor to end of the line
    g_               move cursor to end of last word of the line

    t[character]     move cursor to before the character
    f[character]     move cursor to the character
    ;                repeating forward search
    ,                repeating backward search

    %                move cursor between two brackets
    *                move cursor to repeating next word
    #                move cursor to repeating previous word

    x                delete a character
    dd               delete/cut a line
    D                delete rest of the line from cursor position
    dw               delete word
    d[move cursor]   delete up to the new cursor position
    dt[character]    delete up to the character
    df[character]    delete to the character
    ds'              delete surrounding
    di[              delete inside ]
    da[              delete including ]

    r[character]     replace a character
    C                delete rest of the line and go to insert mode
    cw               change word and go to insert mode
    ct[character]    delete up to the character and go to insert mode
    cf[character]    delete to the character and go to insert mode
    cs'"             change surrounding with "
    ci[              change inside ]
    ca[              change including ]

    ~                swap case of the character
    g~~              swap case of the line

    >                indent right
    <                indent left

    y                copy selected characters/block
    yy               copy a line
    p                paste in down
    P                paste in up
    +p               paste from the clipboard

    u                undo
    ctrl + r         redo

    s[char][char]    search for matching character
    S[char][char]    search for matching character backwards
    /[word]          search for all repeating word forwards
    ?[word]          search for all repeating word backwards
    n                move cursor to repeating word
    N                move cursor to repeating word

    q[character][cmd sequence]q        record a macro to the character
    @[character]     implement macro

    gd               jump to definition
    gf               jump to file in a import

    gb               add another cursor to the repeating word

    gh               hover over cursor

    :sp              split tab horizontally
    :vsp             split vertically
    ctrl + w + hjkl  move cursor to split

    :tabnew [file]   open file in new tab
    :tabp            go to previous tab
    :tabn            go to next tab

### vim editor shortcuts

    ctrl + p         fuzzy search
        [char]       search file name
        ctrl + f     switch modes
        ctrl + j/k   navigate files
        ctrl + t     open file in new tab

    :Ack [char]      search pattern
        ?    a quick summary of these keys, repeat to close
        o    to open (same as Enter)
        O    to open and close the quick fix window
        go   to preview file, open but maintain focus on ack.vim results
        t    to open in new tab
        T    to open in new tab without moving to it
        h    to open in horizontal split
        H    to open in horizontal split, keeping focus on the results
        v    to open in vertical split
        gv   to open in vertical split, keeping focus on the results
        q    to close the quick fix window

    nerd tree
        NERDTreeMapActivateNode o  Open selected files.
        NERDTreeMapOpenSplit    i  Open selected files in horizontal splits.
        NERDTreeMapOpenVSplit   s  Open selected files in vertical splits.
        NERDTreeMapOpenInTab    t  Open selected files in tabs.
            dd  Delete selected files from disk. If open in Vim, they remain open.
            m  Move the selected files to another directory. If open in Vim, the buffer still points to its old location.
            c  Copy selected files to another directory.

### References

[barbarianmeetscoding](https://www.barbarianmeetscoding.com/blog/boost-your-coding-fu-with-vscode-and-vim)

[Fireship](https://www.youtube.com/watch?v=-txKSRn0qeA&ab_channel=Fireship)

[BenAwad](https://www.youtube.com/watch?v=IiwGbcd8S7I&ab_channel=BenAwad)

[MissingSemester](https://www.youtube.com/watch?v=a6Q8Na575qc&feature=emb_rel_pause&ab_channel=MissingSemester)
