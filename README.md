# Matriz-Java
Las matrices son utilizadas casi siempre para juegos. 

COMO SE DECLARA  UNA MATRIZ:

codigo:
Integer [][] nombreMatriz = new Integer[3][4]

COMO SE RECORRE LA MATRIZ:
Para recorrer la matriz se necesitan dos contadores asi:

for(int f=0; f<3; f++)
{
  for(int c=0; c<4; c++)
  {
    System.out.println("Digite numero");
    nombreMatriz[f][c] = lector.nextInt(); ====> se iguala a lo que el usuario ingreso
  }
}
