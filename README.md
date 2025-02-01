var text = createjs.text(
 "the longer I'm with you\
 nthe more I love you",
 "bold 24px Ariel", "#fff");
 text.textAlign = "center";
 text.x = w / 2;
 text.y = h / 2 -text.
 getMeasuredLineHeight();
 stage.addChild(text);
