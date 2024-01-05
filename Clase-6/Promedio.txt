public class Promedio{
  public static void main(String args[]){
   
   int matematicas = 5;
   int biologia    = 8;
   int quimica     = 7;
   int promedio    = 0;

   Promedio = (matematicas + biologia + quimica) / 3;
   
   if(promedio >= 6){
    System.out.println("El alumno aprobó con " + Promedio) 
  } else{
    System.out.println("El alumno reprobó con " + Promedio)    
  }    
 }
}