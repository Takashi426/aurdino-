# aurdino-
###how to create your own libreary and add it to your projet
1)open a aurdino ide write add of two numbes program like as

#include <my_library.h>

void setup()
{
  Serial.begin(9600);
  int result=addtwoint(4,3);
  Serial.println(result);
}
void loop(){}

2)in opened terminal of ide select new tab from rigth coner of ide in that declare function declaraition and save it as .h extention like as
#ifndef my_library_h
#define my_library_h



int addtwoint(int a,int b);


#endif
3)again open new tab write function definition as 
#include "my_library.h"

int addtwoint(int a,int b)
{
  return a + b;
}
and save as .cpp extenction 
5)to look these libreary ->sketh -->show sketh 
   in that copy both files(.h ,.cpp) save open aurdino fine goto library make new folder save their
6)frist opened terminal 
#include <my_library.h>//afetr save libreary add symbol < >

void setup()
{
  Serial.begin(9600);
  int result=addtwoint(4,3);
  Serial.println(result);
}
void loop(){}
..save these example(aurdino->libreary->new libreary  foler->make folder name save theri.

##if you want to add your libreary to github open you libreary in aurdino and your libreary folder ex(my libreary folder)make these folder into zib file
-->if you want to downlode a libreary you downlode extract to libreay or open ide select add zib file open your zib file extract
