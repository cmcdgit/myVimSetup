# This Repo is for vim configurations
# 
# install amix vimrc from "https://github.com/amix/vimrc"
#
# then add this vcomments.vim file inside your "~/.vim_runtime" 
# folder and add whats's below to "~/.vim_runtime/vimrcs/basic.vim"

# """""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""
# " => Comment/Uncomment
# """""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""
# source ~/.vim_runtime/vcomments.vim
# map <C-c> :call Comment()<CR>
# map <C-k> :call Uncomment()<CR>
#
#
#
#
#
#
#
#
#
# adds this grep recursively for word under the cursor
#
# """""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""
# " => Thank you TomNomNom
# """""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""
# " Base64 decode word under cursor
# nmap <Leader>b :!echo <C-R><C-W> \| base64 -d<CR>
#
# " grep recursively for word under cursor
# nmap <Leader>gg :tabnew\|read !grep -Hnr '<C-R><C-W>'<CR>

