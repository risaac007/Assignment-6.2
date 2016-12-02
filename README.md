# Assignment-6.2

Instrument.java******
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package javaapplication67;

/**
 *
 * @author hp1
 */
public abstract class Instrument {
    
    abstract void play();
    
    
    
}


ElectricBassGuitar.java*******

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package javaapplication67;

/**
 *
 * @author hp1
 */
public class ElectricBassGuitar extends StringedInstrument {
    
    
     void numberofstrings(){
        System.out.println("The no of strings in a electric guitar is 4 ");
    }
    
}


ElectricGuitar.java *****


/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package javaapplication67;

/**
 *
 * @author hp1
 */
public class ElectricGuitar extends StringedInstrument {
    
    void numberofstrings(){
        System.out.println("The no of strings in a electric guitar is 2 ");
    }
    
}


JavaApplication67******



/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package javaapplication67;

/**
 *
 * @author hp1
 */
public class JavaApplication67 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        StringedInstrument s=new StringedInstrument();
        ElectricGuitar e1=new ElectricGuitar();
        ElectricBassGuitar e2=new ElectricBassGuitar();
        s.numberofstrings();
        e1.numberofstrings();
        e2.numberofstrings();
        
        
    }
    
}


 StringedInstrument.java*******



/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package javaapplication67;

/**
 *
 * @author hp1
 */
public class StringedInstrument extends Instrument {

    @Override
    void play() {
        
    }
    void numberofstrings(){
    
        System.out.println("The no of strings in the following instruments are ");
        
}}



