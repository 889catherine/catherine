# catherine
program katakancinta;
Uses crt;
var x : char;
z : char;
i : integer;
begin
clrscr;
textcolor(01);
gotoXY(35,2);writeln ('888888888888');
delay (200);
insline;
gotoXY(32,3);writeln ('888888822222228888');
delay (200);
gotoXY(31,4);writeln ('888888822222222288888');
delay (200);
gotoXY(30,5); writeln ('888888222222222228888822228888');
delay (200);
gotoXY(30,6); writeln ('888882222222222222288222222222888');
delay (200);
gotoXY(30,7); writeln ('88888222222222LUV22222222222222288');
delay (200);
gotoXY(31,8); writeln ('8888822222222222222222222222222_88');
delay (200);
gotoXY(32,9); writeln ('88888222222222222222U22222222__888');
delay (200);
gotoXY(33,10); writeln ('888822222222222222222222222___888');
delay (200);
gotoXY(34,11); writeln ('8888222222222222222222222____888');
delay (200);
gotoXY(35,12); writeln ('8888222222222222222222_____888');
delay (200);
gotoXY(36,13); writeln ('8882222222222222222_____8888');
delay(200);
gotoXY(37,14); writeln ('888822222222222______888888');
delay(200);
gotoXY(38,15); writeln ('8888882222______88888888');
delay(200);
gotoXY(39,16); writeln ('888888_____888888888');
delay(200);
gotoXY(40,17); writeln ('88888888888888');
delay(200);
gotoXY(41,18); writeln ('888888888');
delay(200);
gotoXY(42,19); writeln ('888888');
delay(200);
gotoXY(43,20); writeln ('8888');
delay(200);
gotoXY(44,21); writeln ('88');
delay(200);
gotoXY(45,22); writeln ('8');
delay (200);
textcolor(05);
gotoXY(35,2);writeln ('888888888888');
delay (200);
gotoXY(32,3);writeln ('888888822222228888');
delay (200);
gotoXY(31,4);writeln ('888888822222222288888');
delay (200);
gotoXY(30,5); writeln ('888888222222222228888822228888');
delay (200);
gotoXY(30,6); writeln ('888882222222222222288222222222888');
delay (200);
gotoXY(30,7); writeln ('88888222222222LUV22222222222222288');
delay (200);
gotoXY(31,8); writeln ('8888822222222222222222222222222_88');
delay (200);
gotoXY(32,9); writeln ('88888222222222222222U22222222__888');
delay (200);
gotoXY(33,10); writeln ('888822222222222222222222222___888');
delay (200);
gotoXY(34,11); writeln ('8888222222222222222222222____888');
delay (200);
gotoXY(35,12); writeln ('8888222222222222222222_____888');
delay (200);
gotoXY(36,13); writeln ('8882222222222222222_____8888');
delay(200);
gotoXY(37,14); writeln ('888822222222222______888888');
delay(200);
gotoXY(38,15); writeln ('8888882222______88888888');
delay(200);
gotoXY(39,16); writeln ('888888_____888888888');
delay(200);
gotoXY(40,17); writeln ('88888888888888');
delay(200);
gotoXY(41,18); writeln ('888888888');
delay(200);
gotoXY(42,19); writeln ('888888');
delay(200);
gotoXY(43,20); writeln ('8888');
delay(200);
gotoXY(44,21); writeln ('88');
delay(200);
gotoXY(45,22); writeln ('8');
gotoXY(05,13); writeln ('I Luv U');
delay (200);

gotoXY(27,91); writeln ('by. idyn');
delay(200);

textcolor(02);
gotoXY(01,23); writeln ('dhe, selama ini sebenarnya aku sayang kamu');
gotoXY(01,24); writeln ('maukah kamu menjadi pacar saya ?');
writeln ('jawab dengan Y untuk jadian, atau N untuk Menolak');

z := readkey;
delay(1000);
case z of
'Y' : writeln('i love you :”>');
'N' : writeln('i hate you');
else writeln('jawab dhe, tekan Y atau N di keyboard');
z :=readkey;
delay(1000);
case z of
'y' : writeln ('i love you : ^_^ >');
'n' : writeln ('walaupun ditolak, abang tetep cinta neng :( *hikz');
else writeln(' ');
end;

end;
read(z);
end.

