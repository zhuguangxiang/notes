# daily notes

## git
  1. Q: how to attach local git repo to remote ?
     A: git remote add origin git@github.com:YOUR:NAME/YOUR REPO master

## spacemacs & evil(vim)
  0. vim shortcuts
     https://gist.github.com/awidegreen/3854277
  1. Q: how to show line number ?
     A: dotspacemacs-line-numbers t or 'relative
  2. Q: how to copy/cut & paste ?
     A: see https://gist.github.com/robphoenix/9e4db767ab5c912fb558
  3. Q: spell check ?
     A: shortcut, M+$
  4. Q: git project support ?
     A: SPC p p to open a git managed file OR open emacs in git repo
  5. Q: c/c++ supported ?
     A: see https://github.com/syl20bnr/spacemacs/tree/master/layers/%2Blang/c-c%2B%2B
        https://github.com/syl20bnr/spacemacs/tree/master/layers/%2Btags/cscope
        jump uses gtags and cscope, shortcut SPC m g g(spacemacs/jump-to-definition), jump back SPC m g p
        auto-completion is supported automatically
  6. Q: quickly swap current buffer with previous one ?
     A: SPC TAB
  7. Q: how to select one area ?
     A: use vim visual mode, press v and then select text(using hjkl)
  8. Q: how to show invisible characters ?
     A: select one area or full text and then press SPC t w
        replace tabs with spaces, using untabify command, in reverse, using tabify command
  9. Q: how to zoom fonts ?
     A: SPC z x, then = to zoom in, and - to zoom out
  10. Q: find/replace with vim
      A: find /foo <RET>, n next one, N previous one to
         replace :%s/foo/bar/gc, % means the whole buffer, g means replacing all, c means confirmation before replace
  11. Q: current line to displayed at center
      A: zz/z., zb, zt
  12. Q: jump and goto line
      A: goto line: M-g g; goback: ''
## org mode
  1. TODO
  2. Agenda
  3. Write Book/Article
