/*
 *Examen de fin de module sur JAVA 
 * // Gil Van Cayseele 
    // ISA A 
 *  // Examen 2019
 */
package gil.vancayseeleexamenjava2019;


/*La structure du code est la suivante ; 
* Un main qui appelle les fonctions, 

Une fonction impression , qui affiche les tables 
Une fonction initialisation qui assiqne les tables 
une fonction impressionalftable qui n'affiche que les demi-tables
une fonction répartir qui répartit les nombres dans les tables
, cette fonction devra trier les éléments du plus petit au plus grand et répartir un petit, un grand
et ce dans chaque table 

*/
public class GilVancayseeleExamenJava2019 {

    // les int
    int randomumber = 101;
    // les tables 
  static  int [] table  =  new  int [100]  ; // table de base 
  
  int sommeTableA=0;
  int sommeTableB=0;
  int sommeTotal=0;
  
    static  int [] tableB  =  new  int [100]  ;  // table A 
   static  int [] tableA  =   new  int [100]  ;  // Table B
     static  int [] tabledesc  =  new  int [100]  ; 
     
    public static void main(String[] args) {
        Initialisation   ( ); 
        
        insertable ( );
        TriInsertdesc();
        repartir();
        somme();
    //   impressionalfTable ();
     //  Impression( ); 
    } // fin de main
 
    
      static void  Impression  ( )  
{
   
    // affichage du tableau de base
     System.out.println ("Tableau de base");
   int  n  =  table.length - 1 ;
  for (  int  i  =  0 ;  i <= n ;  i ++ ) 
    System.out.print ( table[i] + " , ");
   System.out.println ();
   
        System.out.println ("Ordre Croissant");
   int  p  =  tabledesc.length - 1 ;
  for (  int  i  =  1 ;  i <= n ;  i ++ ) 
    System.out.print ( tabledesc[i] + " , ");
   System.out.println ();
   
    System.out.println (table.length);
    
   
 } // fin impression   
  
      
static void impressionalfTable (){
 
   // affichage des demi tableaux
   // Affichage du tableau réparti dans A
    int  r  =  tableA.length - 1 ;
     System.out.println ("Affichage des demi-tables");
     System.out.println ("Demi Table A");
  for (  int  i  =  0 ;  i <= r ;  i ++ ){ 
      
    System.out.print ( tableA[i] + " , ");
   System.out.println ();
 } // fin de for
System.out.println ("Demi table B");
     int  p  =  tableB.length - 1 ;
  for (  int  i  =  0 ;  i <= r ;  i ++ ){ 
      
    System.out.print ( tableB[i] + " , ");
   System.out.println ();
 } // fin de for

}      // fin de void halftable
    
    // initialisation des valeurs
    static void  Initialisation   ( )  
{
   // remplissage aléatoire du tableau 
   int  n  =  table.length-1 ;
  for (  int  i  =  0 ;  i <= n ;  i ++ ) {
    table[i] =  ( int )( Math.random () * 100 );
    
    
  } // fin de for
 } // fin de void initialisation 
  static void  TriInsertdesc  ( ) 
{
   // sous-programme de Tri par insertion :
     int i, j;
   for (i = 1; i < tabledesc.length; ++i) {
       int elem = tabledesc[i];
       for (j = i; j > 0 && tabledesc[j-1] > elem; j--)
           tabledesc[j] = tabledesc[j-1];
       tabledesc[j] = elem;
   }
    
  
 }
 static void  insertable ( ) 
         // assigne dans la tabledesc les nombres choisit
 {
        int i;
        for(i=0;i<table.length;i++)
        {
      
         tabledesc[i]=table[i];
        }
 
 
 
 }
 
 static void repartir(){
 
     for (int i = 0;i<tableA.length;i++){
     if (table[i]>50){
     tableA[i]=tabledesc[i];
     
     }
     else{
     tableB[i]=tabledesc[i];
     
     }
 
 }
 
 }
 
 static void somme(){
 
 for (int i=0;i<=98;i++){
     int tableAtemp = tableA[i];
     //System.out.println ("valeur temporaire du tableauA"+" "+tableAtemp);
     int tablesumvalue =tableA[i+1];
     //System.out.println ("valeur temporaire du tableauA + table +1"+" "+tablesumvalue);
      int sommeTableA = tableAtemp+tablesumvalue;
      System.out.println ("valeur additionnée Table A"+sommeTableA);
     
      int tableBtemp = tableA[i];
     //System.out.println ("valeur temporaire du tableauA"+" "+tableAtemp);
     int tableBsumvalue =tableA[i+1];
     //System.out.println ("valeur temporaire du tableauA + table +1"+" "+tablesumvalue);
      int sommeTableB = tableBtemp+tableBsumvalue;
      System.out.println ("valeur additionnée Table A"+sommeTableB);
     
      System.out.println ("la somme des tableaux"+sommeTableA+sommeTableB);
 } // end for
 
 } // end void somme
 
 
 
 } // fin du public class    
     
    
    






