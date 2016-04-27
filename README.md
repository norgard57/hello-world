# hello-world
Kerbal Operating System

// Hello World Script.
function pww {
  parameter mesg, horz, vert.
  print mesg at (horz,vert).
}

function pht {
  parameter mesg,color.
  hudtext (mesg,5,2,40,color,true).
}

set horz to 2.
set vert to 5.
pww ("Hello",horz,vert).
pww ("World",horz+7,vert).
pww ("!"horz+13,vert).

wait 10.

pht ("Hello World!,green).
