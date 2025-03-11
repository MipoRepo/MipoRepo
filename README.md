
<link href="https://fonts.googleapis.com/css2?family=C64+Pro+Mono&display=swap" rel="stylesheet">
<div align="center">
  <img width=100% src="https://github.com/MipoRepo/MipoRepo/blob/main/heading_picture.png"  />
</div>


###

<h1 align="left">Hey 👋 What's up?</h1>

###

<p align="left">I'm just starting to use this repository. Things are pretty chaotic here at the moment.</p>
<p align="left">..But finally, I'm starting to edit the readme of my profile.</p>

###

<h2 align="left">About me</h2>

###

<p align="left">✨ Creating bugs since 1984<br>📚 I'm currently learning Full Stack Developement with AI<br>🎯 Goals: To Be Good!<br>🎲 Fun fact: Not so good yet... but working on it! </p>

###

<h2 align="left">I code with</h2>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flask/flask-original.svg" height="40" alt="flask logo"  />
  
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" img width="12"  alt="javascript logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="40" alt="react logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="40" alt="nodejs logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/django/django-plain.svg" height="40" alt="django logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="40" alt="mysql logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="40" alt="typescript logo"  />  
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" alt="html5 logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" alt="css3 logo"  />


  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="40" alt="git logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" height="40" alt="bash logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" height="40" alt="github logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gitlab/gitlab-original.svg" height="40" alt="gitlab logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" height="40" alt="vscode logo"  />

  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" height="40" alt="linux logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/debian/debian-original.svg" height="40" alt="debian logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/oracle/oracle-original.svg" height="40" alt="oracle logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/putty/putty-original.svg" height="40" alt="putty logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" height="40" alt="figma logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/wordpress/wordpress-original.svg" height="40" alt="wordpress logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/canva/canva-original.svg" height="40" alt="canva logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/facebook/facebook-original.svg" height="40" alt="facebook logo"  />
</div>
<div>

###

<div align="right">
<a href="https://gitlab.com/MipoRepo" target="_blank">MipoRepo GitLab - it's a bit quieter over there...</a>
</div>

###

###

<h2 align="right">?</h2>

###

<pre>
.org $0801
.byte $9e, $32, $30, $36, $36, $00, $00

s:
  ldx #$00

p_h:
  lda h, x
  beq p_c
  jsr $ffd2
  inx
  jmp p_h

p_c:
  ldx #$00
  lda #$0d
  jsr $ffd2
  lda #$0a
  jsr $ffd2

p_c_l:
  lda c, x
  beq p_m
  jsr $ffd2
  inx
  jmp p_c_l

p_m:
  ldx #$00
  lda #$0d
  jsr $ffd2
  lda #$0a
  jsr $ffd2

p_m_l:
  lda m, x
  beq end
  jsr $ffd2
  inx
  jmp p_m_l

end:
  rts

h:
  .byte $48, $65, $6c, $6c, $6f, $20, $57, $6f, $72, $6c, $64, $21, $00
c:
  .byte $43, $68, $65, $65, $72, $73, $2c, $00
m:
  .byte $4d, $69, $6b, $6b, $6f, $21, $00

 </pre>
 </body>
</html>
  
</div>

