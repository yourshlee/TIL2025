
# Git, Github에서 오늘 실습 하면서 배운 것: 
   --> 꼭~~ 기억해야 할 것들
## - Repository 만들어 보면서 익히기
- Make one Github repositoty..
- git clone < github repo address > ...
  at my local directory
- touch <화일>, vi <화일>
- git add <화일>
- git commit
- git push origin main

## - Branch 실습
       (local) $ git branch
       (remote) $ git branch -r
       (all) $ git branch -a

       (switch) $ git switch {branch name}
                  git merge
                  
      git remote -v
      git switch fiz
      git branch -D fizz

### - Vim 명령어 기억하기 

#### normal mode
  - h j k l - left, down, up, right
  - i - insert mode
  - v - visual mode
  - ESC - back to normal mode
  - d - delete
  - dd - delete a line
  - y - yank
  - yy - yank a line
  - p - paste
  - u - undo
  - a - append
  - A - append from end of line
  - o - open line(under)
  - O - open line(upper)
  - H - move to the top of the screen
  - L - move to the bottom of the screen

#### Cmd-line mode
- :q - quit
- :q! - override and quit
- :w - write
- :wq - write and quit
- :{num} - Go to {num}th line
