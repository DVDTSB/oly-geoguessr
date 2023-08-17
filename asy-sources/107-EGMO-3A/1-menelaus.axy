pair A = dir(110);
pair B = dir(210);
pair C = dir(330);
draw(A--B--C--cycle);

dot("$A$", A, A);
dot("$B$", B, B);
dot("$C$", C, S);

pair Z = (2*A+B)/3;
pair Y = (3*A+5.5*C)/8.5;
pair X = extension(Z,Y,B,C);

dot("$X$",X, S);
dot("$Y$",Y, NE);
dot("$Z$",Z, NW);


draw(C--X,dashed);

/*
  Source: Menelaus's Theorem
  Points: A B C X Y Z
  Item: X Y Z
  Text: Here $$ \frac{BX}{XC}\cdot\frac{CY}{YA}\cdot\frac{AZ}{ZB}=-1$$ where the lenghts are directed.
*/
