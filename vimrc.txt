syntax on
colorscheme default

"Highlight matching pairs of brackets. Use the '%' character to jump between them."
set matchpairs+=<:>

"Show line numbers"
set number

"Set tab stuff"
set autoindent
set expandtab
set tabstop=4
set softtabstop=4
set shiftwidth=4

"Show status bar"
set laststatus=2

"Set status line display"
set statusline=%F%m%r%h%w\ [FORMAT=%{&ff}]\ [TYPE=%Y]\ [POS=%l,%v][%p%%]\ [BUFFER=%n]\ %{strftime('%c')}

"Highlight matching search patterns"
set hlsearch

set showmode
set showcmd

"Speed up scrolling in Vim"
set ttyfast
