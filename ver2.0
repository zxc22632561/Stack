/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package javaapplication1;

import java.util.Stack;

/**
 *
 * @author user
 */
public class JavaApplication1 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) throws Exception {
        // TODO code application logic here
        
        Stack s = new Stack();
        String str = "{avavav{va}av}}";
        for(int i =0;i<str.length();i++){
            
            char c = str.charAt(i);
            
            if(c=='{'){
                s.push(c);
            }else if(c=='}'){
                if(s.empty()){
                    throw new Exception("unbalanced!");
                }
                s.pop();
            }
        }
       if(s.empty()==false){
           throw new Exception("unbalanced!");
           
       }
    }
    
}
